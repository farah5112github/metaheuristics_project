# Tuning the hyperparameter of a simple CNN(Convolutional Neural Network) architecture using metaheuristics algorithms

Nucleic acids, proteins, carbohydrates and lipids are four important molecules for any organisms and the carbohydrates communicate with other protein molecules and these protein-carbohydrate interactions have several roles in different biological processes. In order to identify protein-carbohydrate interactions, there are several experimental techniques have been performed although weak binding affinity and synthetic complexity of individual carbohydrates has made the study more expensive, time consuming and challenging. Therefore, developing a computational technique for effectively predicting protein-carbohydrate binding sites has become an urgent necessity. The computational approaches concentrate on locating the sites of proteins that bind to carbohydrates.The computational studies involve different structure based and sequence-based methods. There are several structured based methods which have used to predict binding sites from a known protein structure. The problem of above structed-based techniques is that they are dependent on protein structures that are often not available.

A method, SPRTNT-CBH[1]was proposed in which PSSM features along with other predicted sequence and sequence-derived structure based features were employed to train support vector machine(SVM) classifier and it achieved an average of 18.8% sensitivity and 99.6% specificity while tested using 10-fold cross validation on train dataset having 102 protein-carbohydrate complexes and 22.3% sensitivity and 98.8% specificity while tested using an independent test set of 50 protein-carbohydrate complexes. The above-mentioned methods were failed to effectively identify the binding sites as they either results high sensitivity and low specificity or vice versa.

In order to address the above mentioned issues, I have used a simple CNN architecture with two convolution layers, one max-pooling layer, one fully connected layer and two dense layers.There are several parameters involve in a CNN architecture such as typr of optimizer, learning rate, activation function, pool size, batch size, epoch size, epoch number, padding type, stride size, type of loss function, kernel size, fully connected layer size, dropout rate and so on.The prediction success of a CNN architecture highly depends on the optimal values of these parameters.

In this project, two metaheuristics algorithms are used such as Genetic algorithm and Simulated Annealing to optimize the hyperparameters of a CNN architecture.
For genectic algorithm, different parent selection methods, crossover and mutation methods are examined. Different temperatures have been experimented while working with Simulated Annealing algorithm.They are all listed below :

## Codes :
### Genetic_Algorithm_stochastic_sampling_single_point.ipynb :
**Algorithm name :** Genetic Algoirthm, **Parent selection method :** Stochastic universal sampling, **Mutation type :** single, **Crossovertype :** single point
### Genetic_Algorithm_tournament_sampling_single_point.ipynb :
**Algorithm name :** Genetic Algoirthm, **Parent selection method :** tournament, **Mutation type :** single, **Crossovertype :** single point
### Genetic_Algorithm_random_sampling_single_point.ipynb :
**Algorithm name :** Genetic Algoirthm, **Parent selection method :** rank, **Mutation type :** single, **Crossovertype :** single point
### Genetic_Algorithm_random_sampling_roulette_single_point.ipynb :
**Algorithm name :** Genetic Algoirthm, **Parent selection method :** roulette_wheel, **Mutation type :** single, **Crossovertype :** single point

### Genetic_Algorithm_stochastic_sampling_uniform.ipynb :
**Algorithm name :** Genetic Algoirthm, **Parent selection method :** Stochastic universal sampling, **Mutation type :** single, **Crossovertype :** single point
### Genetic_Algorithm_tournament_sampling_uniform.ipynb :
**Algorithm name :** Genetic Algoirthm, **Parent selection method :** tournament, **Mutation type :** single, **Crossovertype :** single point
### Genetic_Algorithm_random_sampling_uniform.ipynb :
**Algorithm name :** Genetic Algoirthm, **Parent selection method :** rank, **Mutation type :** single, **Crossovertype :** single point
### Genetic_Algorithm_random_sampling_roulette_uniform.ipynb :
**Algorithm name :** Genetic Algoirthm, **Parent selection method :** roulette_wheel, **Mutation type :** single, **Crossovertype :** single point 

### Simulated_Annealing_temp_5.ipynb :
**Algorithm name :** Simulated Annealing Algoirthm, **Temperature :** 5 
### Simulated_Annealing_temp_5.ipynb :
**Algorithm name :** Simulated Annealing Algoirthm, **Temperature :** 10
### Simulated_Annealing_temp_5.ipynb :
**Algorithm name :** Simulated Annealing Algoirthm, **Temperature :** 15

## Environmental Setup :
- **Programming Language :** Python <br />
- **Neural Network based library :** Keras <br />
- **Machine Learning based library :** Scikitlearn <br />
- **Web IDE for python :** Google Colab 
- **Other libraries :** Numpy,pandas,matplotlib,pygad etc.

## References :
[1] Taherzadeh, Ghazaleh, et al. "Sequence-based prediction of protein–carbohydrate binding sites using support vector machines." Journal of chemical information and modeling 56.10 (2016): 2115-2122.
