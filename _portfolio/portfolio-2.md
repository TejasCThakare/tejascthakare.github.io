---
title: "High Dynamic Range-Very Cool"
excerpt: "Computational Imaging <br/><img src='/images/lowexpiitm-500x300.jpg'>"
collection: portfolio
---
<br/><img src='/images/lowexpiitm-500x300.jpg'><br/> 
<sub>Low Exposure Image<sub/>


Take the phone camera, point it at the scene where there are light sources and also darkness (i.e., proper coverage of all intensities), and then capture it. The captured picture will have high saturation around the bright light sources and nearly invisible or partially visible areas where the intensity is low.

Go to the exposure adjustment settingin phone camera and capture the same scene with different exposure settings like -2, -1, 0, 1, and 2. (The above image was captured on an iPhone 14 at -2 exposure.) There is a fundamental link between exposure value and amount of photons captured. The sensor detects photon impacts and converts them into an electrical signal to capture the scene. The sensor's response function, aperture, and gain (ISO) all influence the recorded intensity, and the total amount of light recorded is proportional to the exposure time.

Generally speaking, .png, .jpg, or .jpeg images are in 8-bit format (i.e., the camera sensor encodes RGB values in the range of 0 to 2⁸-1 = 255). If the exposure time is too long, the sensor accumulates more light than it can encode, causing pixel saturation. As a result, darker areas are properly exposed while bright parts lose detail due to clipping. On the other hand, if the exposure time is too short, the sensor receives less photons, which results in the bright areas being properly exposed and the darker areas remaining underexposed.

This procedure generates a sequence of images of the same scene shot at different exposure levels, each with variable intensity.  These are known as Low Dynamic Range (LDR) photos because of their limited capacity to capture the entire range of intensity variations in the scene.  These images can be combined to create a single High Dynamic Range (HDR) image that better represents all intensity levels.  This can be accomplished using a variety of exposure stacking methods, including Mertens' method (exposure fusion) and Debevec's method (radiance map recovery), as well as deep learning-based approaches like CNNs and GANs.  These models can be trained on multi-exposure image data, with or without a corresponding ground truth HDR image, for predicting HDR images from a single or several LDR images.



<br/>
<img src="/images/ldrhdr.png" alt="LDR and HDR Image Comparison">
<br/>
<sub>Image (a) is an LDR, and Image (b) is an HDR. (Image Source: <a href="https://doi.org/10.1007/s11554-019-00855-0" target="_blank">A fast coding method for distortion-free data hiding in high dynamic range images</a>)</sub>

