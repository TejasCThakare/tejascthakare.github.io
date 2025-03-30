---
title: "High Dynamic Range-Very Cool"
excerpt: "Computational Imaging <br/><img src='/images/lowexpiitm-500x300.jpg'>"
collection: portfolio
---
<br/><img src='/images/lowexpiitm-500x300.jpg'><br/> 
<sub>Low Exposure Image<sub/>


Take the phone camera, point it at the scene where there are light sources and also darkness (i.e., proper coverage of all intensities), and then capture it. The captured picture will have high saturation around the bright light sources and nearly invisible or partially visible areas where the intensity is low.

Go to the exposure adjustment settingin phone camera and capture the same scene with different exposure settings like -2, -1, 0, 1, and 2. (The above image was captured on an iPhone 14 at -2 exposure.) There is a fundamental relationship between exposure value and the number of photons recorded. The sensor detects photon strikes and transforms them into an electrical signal to record the scene.  The sensor's response function, gain (ISO), and aperture all affect the recorded intensity, and the total amount of light it records is proportional to the exposure duration.

Generally speaking, .png, .jpg, or .jpeg images are in 8-bit format (i.e., the camera sensor encodes RGB values in the range of 0 to 2⁸-1 = 255). If the exposure time is too long, the sensor accumulates more light than it can encode, causing pixel saturation. As a result, darker areas are properly exposed while bright parts lose detail due to clipping. On the other hand, if the exposure time is too short, the sensor receives less photons, which results in the bright areas being properly exposed and the darker areas remaining underexposed.

This process produces a series of images of the same scene taken at different exposure levels, each showing varying intensity. These are referred to as Low Dynamic Range (LDR) images due to their limited ability to capture the full range of intensity variations in the scene. By merging these images, a single High Dynamic Range (HDR) image can be created to represent all intensity levels more accurately. This can be achieved using various exposure stacking methods, such as Mertens' method (exposure fusion) or Debevec’s method (radiance map recovery), or through deep learning-based approaches like CNNs and GANs. These models can be trained on multi-exposure image data, with or without a corresponding ground truth HDR image, to predict HDR images from single or multiple LDR images.


<br/>
<img src="/images/ldrhdr.png" alt="LDR and HDR Image Comparison">
<br/>
<sub>Image (a) is an LDR, and Image (b) is an HDR. (Image Source: <a href="https://doi.org/10.1007/s11554-019-00855-0" target="_blank">A fast coding method for distortion-free data hiding in high dynamic range images</a>)</sub>

