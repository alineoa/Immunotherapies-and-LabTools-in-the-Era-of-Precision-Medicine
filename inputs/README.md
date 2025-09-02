
# Antibody sequence recovery and 3D modeling

1. Search for "pembrolizumab" in the [Drugbank](https://go.drugbank.com/) and save the sequence in the FASTA format.

2. Run ANARCI with the "Martin" numbering scheme to determine the residues corresponding to the Fv [here](https://opig.stats.ox.ac.uk/webapps/sabdab-sabpred/sabpred/anarci/).

3. To correctly identify the CDRs according to Martin, access [here](http://www.bioinf.org.uk/abs/info.html).

4. 3D modeling of Pembrolizumab's Fv can be achievied with multiple tools:
  - [ABodyBuilder2](https://opig.stats.ox.ac.uk/webapps/sabdab-sabpred/sabpred/abodybuilder2/) 
  - [AlphaFold3](https://alphafoldserver.com/)

5. Structure validation with:
   - [MolProbity](https://molprobity.biochem.duke.edu/): check for the clashscore, Ramachandran outliers and MolProbity score.
   - [QMEAN](https://swissmodel.expasy.org/qmean/): check for the QMEANDisCo Global and local quality estimates.

# Interactions prediction
7. 
  - [Protenix](https://protenix-server.com/model/prediction/add)
