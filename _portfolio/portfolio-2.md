---
title: "Few Photons to pass"
excerpt: "High Dynamic Range-Very Cool <br/><img src='/images/lowexpiitm-500x300.jpg'>"
collection: portfolio
---
<br/><img src='/images/lowexpiitm-500x300.jpg'><br/> 
<sub>Low Exposure Image Captured from iPhone14<sub/>

Take the phone camera, point it at the scene where there are light sources and also darkness (i.e., proper coverage of all intensities), and then capture it. The captured picture will have high saturation around the bright light sources and nearly invisible or partially visible areas where the intensity is low.

Go to the exposure adjustment setting and capture the same scene with different exposure settings like -2, -1, 0, 1, and 2. (The above image was captured on an iPhone 14 at -2 exposure.) There is a fundamental relationship between exposure value and the number of photons recorded. The scene is captured by the sensor detecting photon hits and converting them into an electrical signal. The total amount of light captured by the sensor is proportional to the exposure time, and the recorded intensity is influenced by the sensor’s response function, gain (ISO), and aperture.

Generally speaking, .png, .jpg, or .jpeg images are in 8-bit format (i.e., the camera sensor encodes RGB values in the range of 0 to 2⁸-1 = 255). If the exposure time is too long, the sensor accumulates more light than it can encode, causing pixel saturation. This leads to bright areas losing detail due to clipping, while darker areas become properly exposed. Conversely, when the exposure time is too short, the sensor receives fewer photons, causing darker regions to remain underexposed while the bright areas are correctly exposed.

This process results in a stack of images of the same scene captured at different exposure values, each with varying intensity levels. These images are called Low Dynamic Range (LDR) images because they are limited in dynamic range and cannot fully represent the true intensity variations of the real scene. By combining these differently exposed images, we can reconstruct a single High Dynamic Range (HDR) image that accurately represents all intensity levels. This can be achieved using various exposure stacking methods, such as Mertens' method (exposure fusion) or Debevec’s method (radiance map recovery), or through deep learning-based approaches like CNNs and GANs. These models can be trained on multi-exposure image data, with or without a corresponding ground truth HDR image, to predict HDR images from single or multiple LDR images.

<br/>
<img src="/images/ldrhdr.png" alt="LDR and HDR Image Comparison">
<br/>
<sub>Image (a) is an LDR, and Image (b) is an HDR. (Image Source: <a href="https://doi.org/10.1007/s11554-019-00855-0" target="_blank">A fast coding method for distortion-free data hiding in high dynamic range images</a>.)</sub>

