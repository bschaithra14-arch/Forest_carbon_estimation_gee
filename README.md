**Pan-Sharpening of Landsat-9 Imagery for Bangalore**

Pan-sharpening is a remote sensing image fusion technique used to integrate the high spatial resolution of a panchromatic band with the rich spectral information of multispectral bands. In this study, Landsat-9 imagery is pan-sharpened to generate a high-resolution true-color image of Bangalore, enabling improved spatial interpretation of urban and landscape features.

While multispectral bands (Red, Green, Blue) provide critical spectral information, they are limited in spatial resolution. Conversely, the panchromatic band (Band 8) captures finer spatial details but lacks spectral discrimination. 

**Purpose of Pan-Sharpening:**

1. Enhance spatial resolution of multispectral imagery
2. Improve delineation of urban features, such as roads, buildings, and water bodies
3. Preserve spectral fidelity while increasing visual sharpness
4. Support accurate visual interpretation and GIS-based spatial analysis
5. This is particularly valuable for urban environments such as Bangalore, where fine-scale spatial features are critical for land-use and infrastructure studies.

**Methodology: HSV-Based Fusion**

**Hue** and **Saturation** represent the chromatic (color) information derived from the RGB bands.

**Value** (Intensity) represents brightness and spatial detail and is replaced by the high-resolution panchromatic band (Band 8).

This approach injects high-frequency spatial information into the multispectral image while maintaining its original color characteristics, resulting in a spectrally consistent and spatially enhanced RGB image.

**Processing Workflow:**

1. Landsat-9 images from 2023–2024 with minimal cloud cover are selected for the Bangalore region.
2. A median composite is generated to reduce noise and residual atmospheric effects.
3. The RGB image is transformed into HSV color space.
4. The Value component is substituted with the Panchromatic band.
5. The modified HSV image is converted back to RGB to obtain the pan-sharpened output.

**Output:**
The final product is a pan-sharpened true-color image of Bangalore that combines:
the spectral integrity of multispectral data and
the high spatial resolution of the panchromatic band.
