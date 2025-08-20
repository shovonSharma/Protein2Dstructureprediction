# Protein2Dstructureprediction

In This project, the aim is to predict protein 2D structure using primary amino acid seqn.<br>

There are 20 amino acid that make up proteins.<br>
alanine - ala - A <br>
arginine - arg - R <br>
asparagine - asn - N <br>
aspartic acid - asp - D <br>
cysteine - cys - C <br>
glutamine - gln - Q <br>
glutamic acid - glu - E <br>
glycine - gly - G <br>
histidine - his - H <br>
isoleucine - ile - I <br>
leucine - leu - L <br>
lysine - lys - K <br>
methionine - met - M <br>
phenylalanine - phe - F <br>
proline - pro - P <br>
serine - ser - S <br>
threonine - thr - T <br>
tryptophan - trp - W <br>
tyrosine - tyr - Y <br>
valine - val - V <br>

using this primary seqn, protein's 2D structure can be predicted.
in __sst8 (C: Loops and irregular elements, E: β-strand, H: α-helix, B: β-bridge, G: 3-helix, I: π-helix, T: Turn, S: Bend)__ or __sst3__(C, H, E) <br>

To complete this task, i used an encoder only transformer model.

Model : 
![](https://github.com/shovonSharma/Protein2Dstructureprediction/blob/main/protein2Dprediction.png)

Dataset : [casp12 cb513 ts115](https://www.kaggle.com/datasets/tamzidhasan/protein-secondary-structure-casp12-cb513-ts115)
