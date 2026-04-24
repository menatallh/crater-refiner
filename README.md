Crater Rim Detection Preprocessing
Problem Statement
Crater rims are vital landmarks for planetary science and navigation. Yet detecting them in real lunar imagery is tough due to:

Shadows hiding rim portions

Lighting variations across the lunar surface

Broken/eroded edges from geological processes

Surface noise from rocks and other craters

This code is the preprocessing step that prepares images and extracts candidate crater features before final ellipse fitting.

Processing Flow
text
RAW IMAGE → ENHANCE → EDGE DETECTION → CONTOUR EXTRACTION → FILTERING → NMS → ELLIPSE FITTING → OUTPUT
Final Results
Below are the detection results after complete processing:
![Filtered Contours](figures/detected_rims1.png)
![Filtered Contours](figures/detected_rims2.png)
![Filtered Contours](figures/detected_rims3.png)

![Filtered Contours](figures/detected_rims4.png)
![Filtered Contours](figures/detected_rims5.png)
![Filtered Contours](figures/detected_rims6.png)
![Filtered Contours](figures/detected_rims7.png)
