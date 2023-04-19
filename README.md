# Parameter-Optimization-of-SVM
## Sampling Assignment

**Dataset Used:** [Avila Dataset](https://archive.ics.uci.edu/ml/datasets/Avila)

| Number of Instances:  | 10430 |
|-----------------------|--------|
| Number of Attributes: | 10     |

## Dataset Description:
DATA SET DESCRIPTION 
The Avila data set has been extracted from 800 images of the the "Avila Bible", a giant Latin copy of the whole Bible produced during the XII century between Italy and Spain.  
The palaeographic analysis of the  manuscript has  individuated the presence of 12 copyists. The pages written by each copyist are not equally numerous. 
Each pattern contains 10 features and corresponds to a group of 4 consecutive rows.

The prediction task consists in associating each pattern to one of the 12 copyists (labeled as: A, B, C, D, E, F, G, H, I, W, X, Y).
The data have has been normalized, by using the Z-normalization method, and divided in two data sets: a training set containing 10430 samples, and a test set  containing the 10437 samples.

## Attribute Information:
    
Intercolumnar Distance<br> 
Upper Margin<br>
Lower Margin<br>
Exploitation<br>
Row Number<br>
Modular Ratio<br>
Interlinear Spacing<br> 
Weight<br>
Peak Number<br> 
Modular Ratio / Interlinear Spacing<br>
Class: A, B, C, D, E, F, G, H, I, W, X, Y<br>

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Results

The best parameters of SVC for the given dataset are:
- Kernel : rbf
- C : 6.38460 
- Gamma : 0.546304    

The above parameter gave a maximum accuracy of 0.8022

### Convergence graph  : 

![image](https://user-images.githubusercontent.com/79537031/233198251-cdf03b48-a5e2-4012-bc1f-ed98b514241c.png)





## Submission by :
**Name** : Akshit Miglani
<br>
**Roll No** : 102003701


