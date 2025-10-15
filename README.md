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

<img width="1268" height="407" alt="figure3" src="https://github.com/user-attachments/assets/420ae419-6c38-42d0-930d-0aad80592a10" />


A.2 Effect of Hyperparameters on Model Performance
<img width="1235" height="518" alt="image" src="https://github.com/user-attachments/assets/d1c5fbc3-f906-4849-af28-18898fe9e8ca" />


A.3 Seven-Class Confusion Matrices of Various Methods on the MOSI and MOSEI Datasets Note: The
labels -3 to 3 represent strongly negative, weakly negative, negative, neutral, weakly positive, positive, and strongly
positive, respectively
<img width="1282" height="1487" alt="image" src="https://github.com/user-attachments/assets/d4bb7e74-d368-48cc-a5d4-fcd18452e983" />


A.4 Performance under different random missing rates on MOSI and MOSEI. Best results are in bold.
<img width="1053" height="1615" alt="image" src="https://github.com/user-attachments/assets/c4f9dc44-81ce-4658-8beb-ec63526cf095" />



## Note
Our code will be made available at this link after the paper is published.
