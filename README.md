# PUBH6885Project-Fall2020


Steps for protein structure modelling

1. Open Reference_AA.fasta using Jalview.
2. Find the 4715th mutation in the sequence.
3. Copy the part region of the reference sequence that aligned with the 4715th mutation in the middle.
>Reference_AA/4650-4773
DTDLTKPYIKWDLLKYDFTEERLKLFDRYFKYWDQTYHPNCVNCLDDRCILHCANFNVLFSTVFPPTSFGPL
VRKIFVDGVPFVVSTGYHFRELGVVHNQDVNLHSSRLSFKELLVYAADPAMH
4. Paste the selected sequence into Swiss Model: https://swissmodel.expasy.org/interactive, click Build Model.
5. In Model Result window, check the sequence identity and coverage rate. If these two are small, you may want to change another mutation.
6. In Model-Template Alignment, find the mutation in the new protein model corresponding to the genome (If you hover over this mutation, you should see: PRO 324 A), this should be the new mutation position. The model ID and mutation chain will be listed at left side of Model-Template Alignment (7BV2, chain A).
7. Now you should have all the information needed for next step: the model ID, the new mutation position and the mutation chain.
8. Put all information in Dymamut: http://biosig.unimelb.edu.au/dynamut/prediction. 
    Note: PDB Accession is the model ID. Mutation should be P324L since it will mutate from prolin to leucine.
9. Run the prediction. You will get the protein structure model, along with ΔΔG Predictions, Interactomic Interactions, and Deformation and Fluctuation Analysis.
    Note: It may take hours to run the prediction. Please be patient!








