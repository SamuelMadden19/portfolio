# A Short Analysis of Feature Extraction in Electroluminescence Images of Photovoltaic Module Cells

## Full report located in ELPV_FaultDetection.pdg

### Abstract
There has been an exponential increase in the use of photovoltaic (PV) systems, most notably, the photovoltaic solar panel or solar cell. This naturally gives rise to the difficulties of operation and maintenance. With the combined use of unmanned aerial vehicles (UAV) and electroluminescence (EL) imaging, detailed aerial imagery of the PV systems may be collected and inspected for defects. The analysis of these images is a tedious and expensive manual process that can be alleviated by machine learning. An automated approach makes monitoring and upkeep of PV cells feasible.
Goal:
Using a collection of images that convey high spatial resolution, employ a suite of image processing and feature detection / description techniques to produce accurate and cost effective feature extraction.

![An overview of images in the dataset. The darker the red is, the higher is the
likelihood of a defect in the solar cell overlayed by the corresponding color.](./doc/images/overview.jpg)

### The Dataset

The dataset contains 2,624 samples of 300x300 pixels 8-bit grayscale images of
functional and defective solar cells with varying degree of degradations
extracted from 44 different solar modules. The defects in the annotated images
are either of intrinsic or extrinsic type and are known to reduce the power
efficiency of solar modules.

All images are normalized with respect to size and perspective.
Additionally, any distortion induced by the camera lens used to capture the EL images was
eliminated prior to solar cell extraction.


### Citing

If you use this dataset in scientific context, please cite the following
publications:

> Buerhop-Lutz, C.; Deitsch, S.; Maier, A.; Gallwitz, F.; Berger, S.; Doll, B.; Hauch, J.; Camus, C. & Brabec, C. J. A Benchmark for Visual Identification of Defective Solar Cells in Electroluminescence Imagery. European PV Solar Energy Conference and Exhibition (EU PVSEC), 2018. DOI: [10.4229/35thEUPVSEC20182018-5CV.3.15](http://dx.doi.org/10.4229/35thEUPVSEC20182018-5CV.3.15)

> Deitsch, S.; Buerhop-Lutz, C.; Maier, A. K.; Gallwitz, F. & Riess, C. Segmentation of Photovoltaic Module Cells in Electroluminescence Images. CoRR, 2018, [abs/1806.06530](https://arxiv.org/abs/1806.06530)

> Deitsch, S.; Christlein, V.; Berger, S.; Buerhop-Lutz, C.; Maier, A.; Gallwitz, F. & Riess, C. Automatic classification of defective photovoltaic module cells in electroluminescence images. Solar Energy, Elsevier BV, 2019, 185, 455-468. DOI: [10.1016/j.solener.2019.02.067](http://dx.doi.org/10.1016/j.solener.2019.02.067)
