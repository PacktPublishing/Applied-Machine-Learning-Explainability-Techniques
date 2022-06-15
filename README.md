# Applied-Machine-Learning-Explainability-Techniques
Applied Machine Learning Explainability Techniques, Published by Packt


**Making ML models explainable and trustworthy for practical applications using LIME, SHAP & others**

## What is this book about?
Explainable AI is the set of techniques used to demystify the outcome of machine learning and AI models, making the algorithms more trustworthy and transparent by justifying the model predictions. This book will help you learn how to design explainable ML systems for industrial applications considering the best practices.

This book covers the following exciting features: 
* Learn about various explainability methods for designing robust and scalable explainable ML systems
* Use XAI frameworks like LIME, SHAP & others to make ML models explainable for practical problems
* Become well-versed in interpreting models with model-agnostic methods
* Design user centric explainable ML systems using the guidelines provided for industrial applications

If you feel this book is for you, get your [copy]([https://www.amazon.com/dp/180020390X](https://www.amazon.com/Applied-Machine-Learning-Explainability-Techniques-dp-1803246154/dp/1803246154/)) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
X = series.values
X = X.astype('float32')
size = len(X) - 1
train, test = X[0:size], X[size:]
# fit an ARIMA model
model = ARIMA(train, order=(2,1,1)) # Simple ARIMA time series forecast model
model_fit = model.fit()
# forecast
forecast = model_fit.predict(start=366, end=466)
for i in range(len(forecast)):
    forecast[i] = random.random() * 10 + forecast[i]
result = model_fit.get_forecast()
con_interval = result.conf_int(0.05))
```

**Following is what you need for this book:**
This book is designed for scientists, researchers, engineers, architects, and managers who are actively engaged in the field of Machine Learning and related areas. In general, anyone who is interested in problem-solving using AI would be benefited from this book. The readers are recommended to have a foundational knowledge of Python, Machine Learning, Deep Learning, and Data Science. This book is ideal for readers who are working in the following roles:
•	Data and AI Scientists 
•	AI/ML Engineers
•	AI/ML Product Managers
•	AI Product Owners
•	AI/ML Researchers
•	User experience and HCI Researchers


With the following software and hardware list you can run all code files present in the book (Chapter 1-11).

### Software and Hardware List

You can install the software required in any operating system by first installing [Jupyter Notebook or Jupyter Lab](https://jupyter.readthedocs.io/en/latest/install.html) with the most recent version of Python, or install [Anaconda](https://docs.anaconda.com/anaconda/) which can install everything at once. While hardware requirements for Jupyter are relatively modest, we recommend a machine with at least 4 cores of 2Ghz and 8Gb of RAM.

Alternatively, to installing the software locally, you can run the code in the cloud using Google Colab or another cloud notebook service.  

Either way, the following packages are required to run the code in all the chapters (Google Colab has all the packages denoted with a ^):

| Chapter      | Software required                     | OS required                        |
| ------------ | --------------------------------------| -----------------------------------|
| 2 - 9       | ^ Python 3.6+                         | Windows, Mac OS X, and Linux (Any) |
| 2 - 9       | ^ matplotlib 3.2.2+                   | Windows, Mac OS X, and Linux (Any) |
| 2 - 9       | ^ scikit-learn 0.22.2+                | Windows, Mac OS X, and Linux (Any) |
| 2 - 9       | ^ pandas 1.1.5+                       | Windows, Mac OS X, and Linux (Any) |
| 2 - 9       | ^ numpy 1.19.5+                       | Windows, Mac OS X, and Linux (Any) |
| 2 - 9       | ^ seaborn 0.11.1+                     | Windows, Mac OS X, and Linux (Any) |



Alternatively, you can install libraries one chapter at a time inside of a local Jupyter environment using cells with `!pip install` or run all the code in Google Colab. The following are the list of the code tutorials provided for the corresponding chapters for this book: 

- [Chapter 02 - Model Explainability Methods](https://github.com/PacktPublishing/Applied-Machine-Learning-Explainability-Techniques/tree/main/Chapter02)
- [Chapter 03 - Data Centric Approaches](https://github.com/PacktPublishing/Applied-Machine-Learning-Explainability-Techniques/tree/main/Chapter03)
- [Chapter 04 - Introduction to LIME for Model Interpretability](https://github.com/PacktPublishing/Applied-Machine-Learning-Explainability-Techniques/tree/main/Chapter04)
- [Chapter 05 - Practical Exposure of Using LIME in ML](https://github.com/PacktPublishing/Applied-Machine-Learning-Explainability-Techniques/tree/main/Chapter05
- [Chapter 06 - Model Interpretability Using SHAP](https://github.com/PacktPublishing/Applied-Machine-Learning-Explainability-Techniques/tree/main/Chapter06)
- [Chapter 07 - Practical Exposure of Using SHAP in ML](https://github.com/PacktPublishing/Applied-Machine-Learning-Explainability-Techniques/tree/main/Chapter07)
- [Chapter 08 - Human-friendly Explanations with TCAV](https://github.com/PacktPublishing/Applied-Machine-Learning-Explainability-Techniques/tree/main/Chapter08)
- [Chapter 09 - Other Popular XAI Frameworks](https://github.com/PacktPublishing/Applied-Machine-Learning-Explainability-Techniques/tree/main/Chapter09)- 

Remember to make sure you click on the menu item __"File > Save a copy in Drive"__ as soon you open each link to ensure that your notebook is saved as you run it. Also, notebooks denoted with plus sign (+) are relatively compute-intensive, and will take  an extremely long time to run on Google Colab but if you must go to __"Runtime > Change runtime type"__ and select __"High-RAM"__ for runtime shape. Otherwise, a better cloud enviornment or local environment is preferable.  


## Get to Know the Author
**Aditya Bhattacharya**
is an Explainable AI Researcher at KU Leuven with an overall experience of 7 years in Data Science, Machine Learning, IoT & Software Engineering. Prior to his current role, Aditya has worked in various roles in organizations like West Pharma, Microsoft & Intel to democratize AI adoption for industrial solutions. As the AI Lead at West Pharma, he had contributed to forming the AI Centre of Excellence, managing & leading a global team of 10+ members focused on building AI products. He also holds a Masters’s degree from Georgia Tech in Computer Science with ML and a Bachelor’s degree from VIT University in ECE. Aditya is passionate about bringing AI closer to end-users through his various initiatives for the AI community.
