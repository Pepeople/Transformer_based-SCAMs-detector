# Transformer_based-SCAMs-detector

Both the DLS and Assay folders contains:
- Their respective dataset
- DeepSCAM model
- Isolation model
- Random forest model of SCAM detective
- Re-implementation of the deep neural model of SCAM detective
- Re-implementation of the ISE model
- Our transformer model 
- Visualiztion of the features learned by the transformer model using locally linear embedding (LLE) plot.

 We note that in the ISE folder, running the 42-base notebook is sufficient alone as it will run the other nessecary files including:
 - The 119 molecular descriptor file is for extracting molecular features from the data.
 - the 42_base code will run the feature selection and hyper-parameters tuning
 - The blank file will run the model when given a random seed/sate value. The 42_base file will run it once per seed/state
 
 Running the 42_base file is enough as it will run the other files accordingly. 

The following models were reused and adjusted from the following github resrepositories:

[DeepSCAM model](https://github.com/tcorodrigues/DeepSCAMs)
 
[Isolation model](https://github.com/DigiChem/DigitalDiscovery_Perspective/tree/main)

[Random forest model od SCAM detective](https://github.com/alvesvm/scam_detective/tree/master) 

The following were re-implemented in python based on their respective paper:

Re-implementation of the deep neural model of SCAM detective:

Alves, V. M., Capuzzi, S. J., Braga, R. C., Korn, D., Hochuli, J. E., Bowler, K. H., ... & Tropsha, A. (2020). SCAM detective: accurate predictor of small, colloidally aggregating molecules. Journal of Chemical Information and Modeling, 60(8), 4056-4063.

Re-implementation of the ISE model:

Molina, C., Ait-Ouarab, L., & Minoux, H. (2022). Isometric stratified ensembles: a partial and incremental adaptive applicability domain and consensus-based classification strategy for highly imbalanced data sets with application to colloidal aggregation. Journal of Chemical Information and Modeling, 62(8), 1849-1862.

