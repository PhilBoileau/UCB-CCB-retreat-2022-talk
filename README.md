# Flexible Predictive Biomarker Discovery

An endeavor central to precision medicine is predictive biomarker discovery;
they define patient subpopulations which stand to benefit most, or least, from a
given treatment. However, the identification of such biomarkers is often the
byproduct of the related, but fundamentally different, task of treatment rule
estimation. Applying treatment rule estimation methods to identify predictive
biomarkers often results in high false discovery rates. The higher than expected
number of false positives may translate to waste of resources when conducting
follow up experiments of drug target identification and diagnostics assay
development. Patient outcomes are in turn negatively affected. We propose a
variable importance parameter for directly assessing the importance of
potentially predictive biomarkers, and develop a flexible nonparametric
estimation procedure, uniCATE, for this parameter. We prove that our estimator
is double-robust and asymptotically linear under loose conditions on the
data-generating process, permitting valid inference about the metric. The
statistical guarantees of the method are verified in a simulation study
representative of randomized control trials with moderate and high-dimensional
covariate vectors. Our procedure is then used to discover predictive biomarkers
from among the tumor gene expression data of metastatic renal cell carcinoma
patients enrolled in recently completed clinical trials. We find that our
approach more readily discerns predictive from non-predictive biomarkers than
procedures whose primary purpose is treatment rules estimation, and that these
biomarkers delineate more clinically relevant patient subpopulations. An
open-source software for the R programming language of the same name, uniCATE,
will be made available for general use.
