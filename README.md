
# FZA_lensless_imaging
The MATLAB codes allow simulation/experiment and compressive reconstruction of an single-shot lensless imaging using Fresnel zone aperture (FZA). They are based on the paper:

Jiachen Wu, Hua Zhang, Wenhui Zhang, Guofan Jin, Liangcai Cao, and George Barbastathis, "Single-shot lensless imaging with fresnel zone aperture and incoherent illumination," Light: Science & Applications 9, 53 (2020).

Jiachen Wu, Liangcai Cao, and George Barbastathis, "DNN-FZA camera: a deep learning approach toward broadband FZA lensless imaging," Optics Letters 46, 130-133 (2021).


https://www.nature.com/articles/s41377-020-0289-9

FZA_single_shot.m	- simulate the FZA imaging and reconstruction

FZA_single_shot_experiment.m	- reconstruct from experimental image

Contact: clc@tsinghua.edu.cn

Description of the files used in updating the code from ordinary Fresnel zone plate coded imaging to single-focus spiral Fresnel zone plate coded imaging:

Single-shot lensless imaging with fresnel zone.pdf - Supporting paper for the original code

Design Code for Binary Amplitude Spiral Fresnel Zone Plate.docx - Optimization Code Note: Only the design code for the single-focus spiral Fresnel zone plate shall be used; the dual-focus part shall be ignored. The physical object of the zone plate is implemented using an SVG file.

Implementation Scheme of Single-Frame Coded Imaging for Single-Focus Spiral Fresnel Zone Plate Near Sensor.docx - Includes partial code design and optimization schemes; only code‑related and principle‑related content shall be used in the code optimization process.
