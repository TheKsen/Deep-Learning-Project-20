# Deep-Learning-Project-20

This repository groups the work done in the scope of the 02456 Deep Learning Course at DTU.

This is project 20: "Use Foldseek to boost training sets  prediction servers, such as  NetSurfP, by including sequence for similar structures with low sequence homology".

The project was made by Thomas Fayad (s184440) and Oskar Kristoffersen (s184364).

Notebook Files:

Gather_TF: Gathering ASA information from the HTML downloads after inserting the pdb files into the following website:
http://cib.cf.ocha.ac.jp/bitool/ASA/

Embedder_Foldseek: Taking the new protein sequences found with foldseek and creating an embedding for each sequence. The embeddings were then concatenated and saved as a tensor.

Test Data NetSurfP: Randomly taking 500 sequences from the Train_MMseqs.npz file found in the following website:
https://services.healthtech.dtu.dk/service.php?NetSurfP-3.0
The sequences were subsequently embedded and saved as a tensor.

TestMiniNetSurfP: Implementing a miniature version of NetSurfP-3.0 to compare the models with different training sets.



