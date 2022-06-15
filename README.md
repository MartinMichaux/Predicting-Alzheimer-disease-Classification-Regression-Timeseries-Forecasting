# Martin Michaux (i6220118), code from the thesis report "Predict Cognitive Decline" in collaboration with the faculty of Psychology and Neuroscience

## Code contents:

### Classification:
 
    - dataset: includes given original dataset + train/test subsets with the different split percentage
    
    - other tests (no need to really take this into account): concerns others models tests that use Neural Networks but did not have time to finish
    
    - prev_EDA: a data processing step previously done by Rick (advisor from the faculty of Psychology and Neuroscience) on the given original dataset
    
    - class_preprocessing & class_preprocessing_otherData: contains the pre-processing steps we went through from the original dataset & another given dataset with a different method of decline type retrievement
    
    - normalization_techniques: includes different normalization methods we tested on the original dataset
    
    - class_models_binary_RFE & class_models_binary_PCA: includes all experiments done on the pre-processed dataset for the binary classification
    
    - class_models_3_RFE & class_models_3_PCA: includes all experiments done on the pre-processed dataset for the multi-classification
   
    - class_models_org_PCA_tests: contains the tests made on the combination of the PCA of the original dataset + itself on the classification
   
   
   
### Regression:
    
    - dataset: includes given original dataset + train/test subsets with the different split percentage
    
    - other tests (no need to really take this into account): concerns others models tests that use Neural Networks but did not have time to finish
    
    - reg_preprocessing & reg_preprocessing_otherData: contains the pre-processing steps we went through from the original dataset & another given dataset with a different method of decline type retrievement
 
    - reg_models_RFE & reg_models_PCA: includes all experiments done on the pre-processed dataset for the regression
   
    - reg_models_org_PCA_tests: contains the tests made on the combination of the PCA of the original dataset + itself on the regression
    
    
 ### Time-series forecasting:
     
    - dataset: includes given original dataset + train/test subsets with the different split percentage
    
    - tests (no need to really take this into account): concerns others models tests that use Neural Networks but did not have time to finish
    
    - ts_preprocessing: contains the pre-processing steps we went through from the original dataset
    
    - ts_models: includes all experiments done on the pre-processed dataset for the time-series forecasting
