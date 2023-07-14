# Notes

Machine Learning
--
### Hyperparameter tuning or optimization 
Searching for the best configuration of user defined inputs to enable optimal performance.

#### Different Techniques
- **Bayesian Optimization**: it builds a probability model of the objective function and uses it to select hyperparameter to evaluate in the true objective function. That is, if there are unlimited resources, we would compute every single point of the objective function so that we know its actual shape.
  - Surrogate Model is the probability representation of the objective function, which is essentially a model trained on the pairs (hyperparameter, true objective function)
  - Acquisition function is also called the Selection function.
- **Evolutionary algorithms** (EA) are optimization algorithms that work by modifying a set of candidate solutions (population) according to certain rules called Operators. It has proven to perform better than grid search techniques based on an accuracy-speed ratio.
- **Gradient Based Optimization** - based on the computation of the gradient of a machine learning model selection criterion with respect to the hyperparameters. This hyperparameter tuning methodology can be applied when some differentiability and continuity conditions of the training criterion are satisfied.
- **Grid Search** - It performs exhaustive search on the hyperparameter set specified by users.
- **Keras Tuner** - This library helps finding kernel sizes, learning rate for optimization.
- **Population-based Optimization** - These methods are essentially a series of random search methods based on genetic algorithms, such as evolutionary algorithms, particle swarm optimization, among others. One of the most widely used population-based methods is population-based training (PBT) proposed by DeepMind.
  - PBT is unique method in two aspects: 1. It allows for adaptive hyper-parameters during training. It combines parallel search and sequential optimization.
- **ParamILS** -
- **Random Search** - based on basic improvements on Grid Search, it performs randomized search over hyper-parameters from certain distribution over possible parameter values.

Oracle ADS
--
- It speeds common data science activities by providing tools to automate by providing pythonic interface to OCI services, such as OCI Data Science, Object Storage, Autonomous Database, Data Flow.
- Reads datasets from different sources into Pandas dataframes.
- Tunes models using hyperparameter optimization with the ADSTuner tool
- Generates detailed evaluation reports of your model candidates with the ADSEvaluator module.
- Saves machine learning models to OCI Data Science models.
- Deploys models as HTTPS endpoints with Model deployment.
- Launch distributed ETL, data processing, and model training jobs in Spark with OCI Data Flow.
- Train machine learning models in OCI Data Science jobs.
- Distributed training with PyTorch, Horovod and Dask



