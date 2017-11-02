# RDb<sub>2</sub>C-Home
  Here is the home repository for RDb<sub>2</sub>C from [Haipeng Gong's Lab](http://166.111.152.91/).
## What is **RDb<sub>2</sub>C**?
  RDb<sub>2</sub>C (**R**idge-**D**etection-based **β-β** **C**ontact predictor) is a β-β contact predictor designed to refine the predited contact maps from any protein contact prediction algorithms. Here, we provide the package for CCMpred **\[1\]** and RaptorX-Contact **\[2\]** based models. For both methods, there are 2 models for DeepCNF **\[3\]** and DSSP **\[4\]**, respectively. For other input contact map, we provide the training script designed for any input contact maps with little customer modify.
## Download
  The packages could be downloaded from the GitHub release page or our [lab website](http://166.111.152.91/).
  + RDb<sub>2</sub>C-CCMpred-DeepCNF ([GitHub](https://github.com/wzmao/RDb2C/releases/download/1.0/RDb2C_CCMpred_DeepCNF.tar.gz "GitHub")) ([Lab website](http://166.111.152.91/Downloads/RDb2C/RDb2C_CCMpred_DeepCNF.tar.gz "Lab website"))
  + RDb<sub>2</sub>C-CCMpred-DSSP ([GitHub](https://github.com/wzmao/RDb2C/releases/download/1.0/RDb2C_CCMpred_DSSP.tar.gz "GitHub")) ([Lab website](http://166.111.152.91/Downloads/RDb2C/RDb2C_CCMpred_DSSP.tar.gz "Lab website"))
  + RDb<sub>2</sub>C-RaptorX-Contact-DeepCNF ([GitHub](https://github.com/wzmao/RDb2C/releases/download/1.0/RDb2C_RaptorX_DeepCNF.tar.gz "GitHub")) ([Lab website](http://166.111.152.91/Downloads/RDb2C/RDb2C_RaptorX_DeepCNF.tar.gz "Lab website"))
  + RDb<sub>2</sub>C-RaptorX-Contact-DSSP ([GitHub](https://github.com/wzmao/RDb2C/releases/download/1.0/RDb2C_RaptorX_DSSP.tar.gz "GitHub")) ([Lab website](http://166.111.152.91/Downloads/RDb2C/RDb2C_RaptorX_DSSP.tar.gz "Lab website"))
## Other Data
  We also listed the predicted result for BetaSheet916 and BetaSheet1452 in our paper.

|    | BetaSheet916 | BetaSheet1452|
|----|------|----|
|CCMpred-DeepCNF | [GitHub](https://github.com/wzmao/RDb2C/blob/master/Data/916-CCMpred-DeepCNF.7z?raw=true "GitHub"), [Lab website](http://166.111.152.91/Downloads/RDb2C/916-CCMpred-DeepCNF.7z "Lab website")  | [GitHub](https://github.com/wzmao/RDb2C/blob/master/Data/1452-CCMpred-DeepCNF.7z?raw=true "GitHub"), [Lab website](http://166.111.152.91/Downloads/RDb2C/1452-CCMpred-DeepCNF.7z "Lab website")|
|CCMpred-DSSP | [GitHub](https://github.com/wzmao/RDb2C/blob/master/Data/916-CCMpred-DSSP.7z?raw=true "GitHub"), [Lab website](http://166.111.152.91/Downloads/RDb2C/916-CCMpred-DSSP.7z "Lab website")  | [GitHub](https://github.com/wzmao/RDb2C/blob/master/Data/1452-CCMpred-DSSP.7z?raw=true "GitHub"), [Lab website](http://166.111.152.91/Downloads/RDb2C/1452-CCMpred-DSSP.7z "Lab website")|
|RaptorX-Contact-DeepCNF | [GitHub](https://github.com/wzmao/RDb2C/blob/master/Data/916-RaptorX-DeepCNF.7z?raw=true "GitHub"), [Lab website](http://166.111.152.91/Downloads/RDb2C/916-RaptorX-DeepCNF.7z "Lab website") (858) | |
|RaptorX-Contact-DSSP | [GitHub](https://github.com/wzmao/RDb2C/blob/master/Data/916-RaptorX-DSSP.7z?raw=true "GitHub"), [Lab website](http://166.111.152.91/Downloads/RDb2C/916-RaptorX-DSSP.7z "Lab website") (858) | |
## Training Script
  We provide the training script for any contact map prediction algorithm, see the README file for detail information.

  [GitHub](https://github.com/wzmao/RDb2C/blob/master/RDb2C_Train.tar.gz?raw=true "GitHub"), [Lab website](http://166.111.152.91/Downloads/RDb2C/RDb2C_Train.tar.gz "Lab website")
<!-- ## Cite Us
  Please cite us as following:
  > ... -->
## Reference
  > 1. Seemayer S, Gruber M, Söding J. CCMpred—fast and precise prediction of protein residue–residue contacts from correlated mutations. Bioinformatics. 2014;30(21):3128-30.
  > 2. Wang S, Sun S, Li Z, Zhang R, Xu J. Accurate De Novo Prediction of Protein Contact Map by Ultra-Deep Learning Model. PLoS Computational Biology. 2017;13(1):e1005324.
  > 3. Wang S, Weng S, Ma J, Tang Q. DeepCNF-D: predicting protein order/disorder regions by weighted deep convolutional neural fields. International journal of molecular sciences. 2015;16(8):17315-30.
  > 4. Kabsch W, Sander C. Dictionary of protein secondary structure: pattern recognition of hydrogen‐bonded and geometrical features. Biopolymers. 1983;22(12):2577-637.
