# Transformer_based-SCAMs-detector

Both the DLS and Assay folders contains:
- Their respective dataset
- DeepSCAM model
- Isolation moel
- Random forest model of SCAM detective
- Re-implementation of the deep neural model of SCAM detective
- Re-implementation of the ISE model
- Our transformer model 
-The t-SNE plot of the features learned by our transforer model 

 We note that in the ISE folder, running the 42-base notebook is sufficient alone as it will run the other nessecary files including:
 - The 119 molecular descriptor file is for extracting molecular features from the data.
 - the 42_base code will run the feature selection and hyper-parameters tuning
 - The blank file will run the model when given a random seed/sate value. The 42_base file will run it once per seed/state
 
 Running the 42_base file is enough as it will run the other files accordingly. 
