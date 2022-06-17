# Model based desicion making
_Group 13 readme_

M.E. Glowacki 
E.M. ter Hoeven
C.W. Ouwehand
T.R. Sandbergen
M.P. Streng
M.   Verhagen


In this readme an overview of the used code is given. Most work is done in Jupyter Notebooks. The ones that are significantly modified and used for the analysis in the main report, are listed below:

- [Open exploration](1 Open exploration Group 13_v2.ipynb): Open exploration
- [Sobol G13.ipynb](2 Sobol G13.ipynb): SOBOL analysis
- [PRIMG13.ipynb](3 PRIMG13.ipynb): PRIM and dimensional stacking
- [Optimization policies.ipynb](4 Optimization policies.ipynb): MORDM, MORDM robustness & MORDM Max regret
- [MORO robustness optimization.ipynb](5 MORO robustness optimization.ipynb): MORO robust policy selection 

The following files have been used for the debate:

- [Problem Formulations](6 Problem Formulations.ipynb): Searches empirically for optimal policies for Zuthen
- [Rijkswaterstaat policies](7 Rijkswaterstaat policies.ipynb): Checks the policies that have been proposed by Rijkswaterstaat

# Pickles
Pickles: Note that in all of these Notebook files pickles have been used. These pickles have been used to save the data of every run. By setting the pickle at *True*, the Pthon file will use the data of the previous run to process for example graphs or Dataframes. By setting the pickle at *False* the entire model will restart the run and save it into a pickle. This will demand a significant amount of computational power and is only advised for external validation.

# Data storage
Furthermore all data has been stored in the *data* file. This file contains for instance all the pickle files that have been made.

# Figures
The figures have been stored in the *images* file. If a Jupyter Notebook plots a figure again, the figure in the image file will be overwritten.