# HiGraMI

Pytorch implementation of the paper: 
> **[HIGRAMI]**



## Data Preparation
MOSI/MOSEI= Download: Please see [MMSA](https://github.com/thuiar/MMSA)

## Environment
The basic training environment for the results in the paper is Pytorch 2.2.1, Python 3.11.7 with 3090. 

## Training
You can quickly run the code with the following command:
```
bash train.sh
```

## Appendix
A.1 Audio–visual feature similarity comparison.
(a) Average cosine similarity between visual and audio features under time-step alignment. (b) Local peak similarity between visual and audio features.

![Audio–visual feature similarity comparison.](figure3.png)

A.2 Effect of Hyperparameters on Model Performance
![Effect of Hyperparameters on Model Performance](image.png)

A.3 Seven-Class Confusion Matrices of Various Methods on the MOSI and MOSEI Datasets Note: The
labels -3 to 3 represent strongly negative, weakly negative, negative, neutral, weakly positive, positive, and strongly
positive, respectively
![Seven-Class Confusion Matrices](image-1.png)

A.4 Performance under different random missing rates on MOSI and MOSEI. Best results are in bold.
![Performance under different random missing rates on MOSI and MOSEI](image-2.png)


## Note
Our code will be made available at this link after the paper is published.
