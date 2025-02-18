To achieve rapid and precise identification of water supply pipeline leakage faults, this 
study introduces a diagnostic framework that integrates multisource multiscale attention entropy 
(MMATE), an enhanced least-squares twin support vector machine (ELSTSVM), and an adaptive 
boosting (AdaBoost) algorithm. The MMATE-ELSTSVM-AdaBoost architecture follows a threestage
workflow. First, an improved wavelet threshold denoising (IWTD) technique featuring a novel 
threshold-processing function is developed to suppress signal noise. Second, MATE values are 
extracted from the denoised signals, and a multidimensional feature vector is constructed by 
integrating MATE characteristics across multisource sensors. Third, the ELSTSVM’s objective 
function is enhanced through a reformulated distance metric, augmented with regularization and 
compactness terms to optimize model robustness and generalizability. The refined MMATE feature 
vectors are then fed into the ELSTSVM-AdaBoost ensemble for fault classification. Experimental 
evaluations demonstrate that the proposed framework significantly outperforms conventional 
single-feature approaches, standalone models, and state-of-the-art SVM variants, achieving a peak 
classification accuracy of 99.10% in leakage detection tasks. 
These pipeline leakage faults data were derived from the following resources available in the public domain: 
[[list resources and URLs](https://data.mendeley.com/datasets/tbrnp6vrnj/1)]
