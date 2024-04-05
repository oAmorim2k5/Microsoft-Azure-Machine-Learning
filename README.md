# 🧠 Microsoft Azure AI Rentals
This is my first project with Microsoft Azure, I create a model to calculate a bike rentals.

## How I create my project

- First I register my account on Microsft: Azure 

> After this I watch the class video from DIO Microsoft: Azure AI Fundamentals bootcamp to learn how I can use Microsoft: Azure.
> Then watched the video I go my hands work and create my project.

## First Step

- Create a workspace Machine Learn on Azure.

> Using the [Azure Documentation](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#use-automated-machine-learning-to-train-a-model) I did create my workspace using the predetermined data.

## Second Step

- Use automated machine learning to train a model

> On this step we will use the machine learn to train our models to identify our bicycle rentals creating our machine learn.
Using Azure [Documentation](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#use-automated-machine-learning-to-train-a-model).

## Third Step

- Review the best model

> In this step we will review the best model and see the graphics.

## Forty Step

- Deploy and test the model

> Finally we will test our model using the json data from the [Documentation](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#use-automated-machine-learning-to-train-a-model)

### Input:
``` {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }
```
### Expectated  someone like this Output:

```
{
    "Results":[1 item
        0:float476.0098039772323
    ]
}
```

## 📖 Documentation

- [**Microsoft: Azure doc**](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#use-automated-machine-learning-to-train-a-model)

- [**DIO Class**](https://web.dio.me/lab/trabalhando-com-machine-learning-na-pratica-no-azure-ml/learning/88f82571-5450-40a9-9f4d-253416f2530e)

### Obs.. I'm working in my english..

