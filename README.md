# Neural Networks with COVID-19 & Adversarial Attacks

COVID - 19, a new virus, currently poses a major global threat. It has infected more than one million people worldwide and resulted in hundreds of thousands of deaths. The problem in developing such a prediction system is the need for more general knowledge about how the virus will spread and the number of cases per day. Therefore, the prediction model must be able to infer the situation from past data so that the results show a future trend and may be closely related to real numbers. Following this logic, the thesis can build a model based on existing research and then use it to predict future COVID -19 cases in Rhineland-Palatinate. The thesis discusses the results in building a neural network model for COVID -19 spread prediction for the dissertation. The predictor is based on a standard neural network architecture technique that learns with the training model of an artificial neural network. In the second part of the thesis, working on some manipulations to see if the training model also performs as it usually does. This would mean that the thesis talks about the different adversarial attacks. These adversarial attacks will show us different ways to perform the manipulations to see how the model performs.

# Research Questions:

- **RQ1**- Does the thesis implement the paper with the RLP data?
- **RQ2**- What different factors can be improved to make the model predict better?
- **RQ3**- Can we manipulate the data/model in a way such that the results produced by this perturbed data is very similar to the original?


## Requirements 

- **Hardware**
    - Minimum Requirements:  
        - **OS**: Windows / Linux
        - **Processor**: Intel Core i5 / AMD FX-8310
        - **Memory**: 8 GB RAM

    - **Recommended Requirements**:  
        - **OS**: Windows / Linux
        - **Processor**:  Intel Core i7 / AMD Ryzen 3 3200G
        - **Memory**: 8/16 GB RAM

    - **Other Runtime Environment**
      - Google Collab
      - AWS SageMaker

- **Software**
    - [Python 3.x](https://www.python.org/downloads/)

## Python Dependency Installation

```bash
pip install -r requirement.txt
```

## Data

The data is provided in seperate Covid19 dataset [repository](https://github.com/gayatritawada2/covid_dataset.git).

Note: Jupyter notebooks will automatically fetch dataset.

## Source Code

The code is working with different time steps and each time step is a different jupyter notebook. 

