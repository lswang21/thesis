# Princeton University Senior Thesis Code, Lucy S. Wang '21

This public repository contains the R Code used in the visualization and modeling of two Ni/photoredox-catalyzed cross-electrophile couplings of epoxides with aryl iodides. 

## Files 

### Enantioselective Photo-assisted Cross-Electrophile Coupling of Styrene Oxides with Aryl Iodides (EPARC) 
1. EPARC Epoxide Nested CV OLS: Ordinary Least Squares (Multivariate Linear Regression) using the Repeated, Stratified Nested Cross Validation Scheme; also contains 5x2 Protocol 
2. EPARC Nested LASSO: Nested LASSO scheme, with outer loop of repeated CV and inner loop (10-fold CV) to select hyperparameter
3. EPARC Comparison of Ligand Representation: Conducts statistical hypothesis tests (one way repeated measures ANOVA, Friedman's tests) to compare performance of winning models across ligand representations (LNiArCl, LNiF2, free ligand) 
4. EPARC PCA: Conducts PCA of EPARC datasets, generates Scree plots, PCA plots, and loading scores 

### Photo-assisted Cross-Electrophile Coupling of Epoxides with Aryl Iodides (PARC)
1. PARC Transformed Nested CV OLS: Ordinary Least Squares (Multivariate Linear Regression) using the Repeated, Stratified Nested Cross Validation Scheme; applies log-transformation and backtransformation with Duan's smearing estimate (1983)
2. PARC Transformed Nested LASSO: Nested LASSO scheme, with outer loop of repeated CV and inner loop (10-fold CV) to select hyperparameter; applies log-transformation and backtransformation with Duan's smearing estimate (1983)
3. PARC Visualizations: Heatmaps, correlation plots, feature/output distributions, and PCA 
