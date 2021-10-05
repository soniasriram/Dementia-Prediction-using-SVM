# Dementia-Prediction-using-SVM
# Mini-Project: Dementia prediction using SVM

# Problem Statement
**Prediction of Dementia using an SVM model on brain MRI features

# Learning Objectives
At the end of the mini-project, you will be able to :

1. perform data exploration, preprocessing and visualization
2. implement SVM Classifier on the data
3. explore various parameters of SVM classifier and implement OneVsOne classifier
4. calculate the metrics and plot the roc_curve

# Information about
**About Dementia

Dementia is a general term for loss of memory and other mental abilities severe enough to interfere with daily life. It is caused by physical changes in the brain. Alzheimer's is the most common type of dementia, but there are many kinds.

Brain Imaging via magnetic resonance imaging (MRI) and Machine Learning

MRI is used for the evaluation of patients with suspected Alzheimer's disease
MRIs detect both, local and generalized shrinkage of brain tissue.
MRI features predict the rate of decline of AD and may guide therapy in the future
Using machine learning on MRI features could help in automatedly and accurately predicting the progress of a patient from mild cognitive impairment to dementia
To understand the basics of MRI technique, you could refer here

# Dataset
The dataset chosen for this mini-project is OASIS - Longitudinal brain MRI Dataset. This dataset consists of a longitudinal MRI collection of 150 subjects aged 60 to 96. Each subject was scanned on two or more visits, separated by at least one year for a total of 373 imaging sessions. For each subject, 3 or 4 individual T1-weighted MRI scans obtained in single scan sessions are included. The subjects are all right-handed and include both men and women. 72 of the subjects were characterized as nondemented throughout the study. 64 of the included subjects were characterized as demented at the time of their initial visits and remained so for subsequent scans, including 51 individuals with mild to moderate Alzheimer’s disease. Another 14 subjects were characterized as nondemented at the time of their initial visit and were subsequently characterized as demented at a later visit.

# Dataset fields:

Subject ID - Subject Identification
MRI ID - MRI Exam Identification
Group - Target variable with 3 labels ('NonDemented', 'Demented', 'Converted')
Visit - Visit order
MR Delay - MR Delay Time (Contrast)
M/F - Male or Female
Hand - Unique value 'R'
MMSE - Mini-Mental State Examination score (range is from 0 = worst to 30 = best)
CDR - Clinical Dementia Rating (0 = no dementia, 0.5 = very mild AD, 1 = mild AD, 2 = moderate AD)
Derived anatomic volumes
eTIV - Estimated total intracranial volume, mm3
nWBV - Normalized whole-brain volume, expressed as a percent of all voxels in the atlas-masked image that are labeled as gray or white matter by the automated tissue segmentation process
ASF - Atlas scaling factor (unitless). A computed scaling factor that transforms native-space brain and skull to the atlas target (i.e., the determinant of the transform matrix)
For learning more on building a machine learning model to predict dementia using SVM, refer here.
