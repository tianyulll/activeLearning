I implemented different active learning heuristics from scratch and compared the performance on two types of dataset: classification and regression.
For each heuristic method, I run 10 simulations and take the average of the evaluation metrics.
Heuristics methods including: uncertainty sampling, query by committee(mellow & aggressive), minimization of expected risk, density-based sampling, design of experiments, batch sampling.
For the base learn, I used a variety of models available in SciKitLearn.