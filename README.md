#VVD-structures

REPOSITORY FOR HOMOLOGY MODELS FOUND IN THE VISION VARIATION DATABASE

This repository has a selected collection of structures for genes found in the Vision Variation Database. Each model has at least a 30% sequence identity and was taken from SWISS-MODEL (http://swissmodel.expasy.org) or ModBase (http://modbase.compbio.ucsf.edu/modbase-cgi/index.cgi). These models were then refined using the FFX force field. More information about FFX can be found by visiting the URL: http://ffx.biochem.uiowa.edu.

Each structure underwent the following procedure-local minimization, rotamer optimization, and another local minimization. Local minimization follows the energy landscape of the protein structure to approximate the lowest-energy conformation. Rotamer optimization filters through all of the discretized side-chain positions (with a fixed backbone) to predict the most likely structure conformation. The final minimization allows the rigid rotamer structure to relax and find its new lowest-energy conformation. 

The results are summarized in the VVD-structures-results.xlsx file. MolProbity was the scoring tool used to evaluate the original and refined structures. MolProbity compares the inputted structure against the structures deposited in the PDB. The scoring function outputs the approximate atomic resolution of the inputted structure; therefore, a smaller MolProbity score is better. For more information about MolProbity, visit http://molprobity.biochem.duke.edu/. The average structure score before FFX refinement was 3.1 angstroms (38th percentile); however, the average FFX structure scored 1.6 angstroms (75th percentile).

The following organization is used for this database: the root directory is the database itself. It is called VVD-variants. Each directory is labeled by gene name. Within each directory are subdirectories for the residue range of the homology models that belong to the specific gene. Each subdirectory contains the non-refined (original) model, FFX-refined model, and PDF documents of the MolProbity results of both the original and refined models. For example, if you select the NR2E3 directory from the root directory, you will have access to the two different residue ranges documented for NR2E3. After selecting the residue range 206-408, you will find the original and refined PDB files and the MolProbity reports for both structures.

If you have any questions, please do not hesitate to contact me at ava-lynn@uiowa.edu.


