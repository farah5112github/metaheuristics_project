# Tuning the hyperparameter of a simple CNN(Convolutional Neural Network) architecture using metaheuristics algorithms

Nucleic acids, proteins, carbohydrates and lipids are four important molecules for any organisms, among them carbohydrates come after the DNA and proteins and which is thought about the third important molecule of life. The carbohydrates communicate with other protein molecules and these protein-carbohydrate interactions have several roles in different biological processes.Moreover, they provide a protection of human cell against pathogens as well as they play an important role as biomarkers or drug targets.

In order to identify protein-carbohydrate interactions, there are several experimental techniques have been performed although weak binding affinity and synthetic complexity of individual carbohydrates has made the study more expensive, time consuming and challenging. Therefore, developing a computational technique for effectively predicting protein-carbohydrate binding sites has become an urgent necessity. The computational approaches concentrate on locating the sites of proteins that bind to carbohydrates.The computational studies involve different structure based and sequence-based methods. There are several structured based methods which have used to predict binding sites from a known protein structure. The problem of above structed-based techniques is that they are dependent on protein structures that are often not available.

A method, SPRTNT-CBH[1]was proposed in which PSSM features along with other predicted sequence and sequence-derived structure based features were employed to train support vector machine(SVM) classifier and it achieved an average of 18.8% sensitivity and 99.6% specificity while tested using 10-fold cross validation on train dataset having 102 protein-carbohydrate complexes and 22.3% sensitivity and 98.8% specificity while tested using an independent test set of 50 protein-carbohydrate complexes. The above-mentioned methods were failed to effectively identify the binding sites as they either results high sensitivity and low specificity or vice versa.

In order to address the above mentioned issues, I have used a simple CNN architecture with two convolution layers, one max-pooling layer, one fully connected layer and two dense layers.There are several parameters involve in a CNN architecture such as typr of optimizer, learning rate, activation function, pool size, batch size, epoch size, epoch number, padding type, stride size, type of loss function, kernel size, fully connected layer size, dropout rate and so on.The prediction success of a CNN architecture highly depends on the optimal values of these parameters.

In this project, two metaheuristics algorithms are used such as Genetic algorithm and Simulated Annealing to optimize the hyperparameters of a CNN architecture.
For genectic algorithm, different parent selection methods, crossover and mutation methods are examined. Different temperatures have been experimented while working with Simulated Annealing algorithm.They are all listed below :

#### Genetic_Algorithm_stochastic_sampling_single_point.ipynb :
**Algorithm name :** Genetic Algoirthm  <br />
**Parent selection method :** Stochastic universal sampling  <br />
**Mutation type :** single  <br />
**Crossovertype :** single point  <br />
#### Genetic_Algorithm_tournament_sampling_single_point.ipynb :
**Algorithm name :** Genetic Algoirthm  <br />
**Parent selection method :** tournament  <br />
**Mutation type :** single  <br />
**Crossovertype :** single point  <br />
#### Genetic_Algorithm_random_sampling_single_point.ipynb :
**Algorithm name :** Genetic Algoirthm  <br />
**Parent selection method :** rank  <br />
**Mutation type :** single  <br />
**Crossovertype :** single point  <br />
#### Genetic_Algorithm_random_sampling_roulette_single_point.ipynb :
**Algorithm name :** Genetic Algoirthm  <br />
**Parent selection method :** roulette_wheel  <br />
**Mutation type :** single  <br />
**Crossovertype :** single point  <br />

#### Genetic_Algorithm_stochastic_sampling_uniform.ipynb :
**Algorithm name :** Genetic Algoirthm  <br />
**Parent selection method :** Stochastic universal sampling  <br />
**Mutation type :** single  <br />
**Crossovertype :** single point  <br />
#### Genetic_Algorithm_tournament_sampling_uniform.ipynb :
**Algorithm name :** Genetic Algoirthm  <br />
**Parent selection method :** tournament  <br />
**Mutation type :** single  <br />
**Crossovertype :** single point  <br />
#### Genetic_Algorithm_random_sampling_uniform.ipynb :
**Algorithm name :** Genetic Algoirthm  <br />
**Parent selection method :** rank  <br />
**Mutation type :** single  <br />
**Crossovertype :** single point  <br />
#### Genetic_Algorithm_random_sampling_roulette_uniform.ipynb :
**Algorithm name :** Genetic Algoirthm  <br />
**Parent selection method :** roulette_wheel  <br />
**Mutation type :** single  <br />
**Crossovertype :** single point  <br />

#### Simulated_Annealing_temp_5.ipynb :
**Algorithm name :** Simulated Annealing Algoirthm  <br />
**Temperature :** 5 
#### Simulated_Annealing_temp_5.ipynb :
**Algorithm name :** Simulated Annealing Algoirthm  <br />
**Temperature :** 10
#### Simulated_Annealing_temp_5.ipynb :
**Algorithm name :** Simulated Annealing Algoirthm  <br />
**Temperature :** 15

For simulated Annealing I have used different temperatures. In the table, instead of single, I have to wirte "random" mutation.
They are all listed below :

![image](https://user-images.githubusercontent.com/60771070/124295420-a2dfc880-db7a-11eb-8230-fc983d165f6c.png)

## References :
[1] Taherzadeh, Ghazaleh, et al. "Sequence-based prediction of protein–carbohydrate binding sites using support vector machines." Journal of chemical information and modeling 56.10 (2016): 2115-2122.
