
# Rice production analysis

This is the end-to-end project it was helpful for the paddy farmmer.In this project we can predict the total production of rice in terms of kg.
In this prediction help to that farmers they are interested in what is the amount of fertilizers, prestisides and seed is to requrired for maximize the output.
Also find the what is the total havesting cost according to your production, and what price are you set per kg if you are selling the market.  



## About rice

In that analysis we can collect secondary data in Kaggle.India is one of leading countries in the world in production of a number of crops including Rice. Rice is one of the world's most important staple food products. This statement is particularly applicable to the Asian continent where rice forms the main staple food for the majority of the population (in particular the poorer segments of society) and where farmers account for more than 90 percent of the world's total rice production.

 Rice Production in Indonesia is an important part of the national economy. Indonesia is the third largest Producer of rice in the world Leading rice producers, with Paddy production in 2003 of more than 50 million tones and cultivated Area of more than 11.5 million. Since 1980, Indonesia’s National rice yield has been Highest in tropical Asia. 

 Recent developments in the rice sector, Indonesia is the world’s third-largest rice producer and also one of the world’s biggest rice consumers. The country’s rice area expanded from 11.4 million ha in 1995 to 13.2 million ha in 2010, which represented 24% of the total agricultural area. Rice yield increased slightly from 4.3 t/ha in 1995 to 5 t/ha in 2010. Rice is the most important food crop in the country. 
 
 ![rice_pic](https://user-images.githubusercontent.com/109405138/210088821-422eee03-ee3f-4bcb-b6b5-b051ab384eb6.PNG)

## Overview
The motivation was to experiment with end to end machine learning project and get some idea about deployment platform like [render](https://dashboard.render.com/).

It is consisted of 19 predict variables and 1 response variable. The variables are Id, Size, Status, Varieties, Bimas, Seed, Urea, Phosphate, Pesticide, Pseed, Purea, Pphosph, Hiredlabor, Famlabor, Wage, Goutput, Noutput, Price,Region.

After randomly selecting 1026 observation and 20 variables were taken 7 significant variables to fit a linear model to predict output having 85% accuracy. Also predicting harvesting cost and price of rice using KNN regressor with 90% accuracy
## Features
Below is the features are highly affected by the selection of the correct price of the mobile.

- Size_hector		:the total area cultivated with rice, measured in hector.
- Varieties		:one of ‘trad’ (traditional varieties), ‘high’ (high yielding varieties) and ‘mixed’  (mixed varieties)
- pSeed			:seed in kilogram.
- Urea			:urea in kilogram
- Phosphate		:phosphate in kilogram pesticide.
- Pesticide		:cost in Rupiah.
- labor		:  labor in hours
- Wage			: labor wage in Rupiah per hour.	
- Goutput		: gross output of rice in kg.
- Price			: price of rough rice in Rupiah per kg.
- Region	: ‘wargabinangun’, ‘langan’, ‘gunungwangi’, ‘malausma’, ‘sukaambit’, ‘firangi’

## PowerBI Dekstop
Power BI is a technology-driven business intelligence tool provided by Microsoft for analyzing and visualizing raw data to present actionable information. It combines business analytics, data visualization, and best practices that help an organization to make data-driven decisions.

We can create the visual on PowerBI report to check the relation between features, those are play importat role on the prediction.
PowerBI is good platform for just click to create the visuals and push the online powerbi service to connect so many peaple to create visuals in same time or send to others.
In the more details [click here](https://powerbi.microsoft.com/en-us/desktop/) to check more details about PowerBI.
## Report
Here is the report for PowerBI

![Capture1](https://user-images.githubusercontent.com/109405138/192024045-08339fe4-c76e-4e2b-987c-c5fb78fa8a4f.PNG)

## Installation
```bash
  Pip install requrement.txt
```
```bash
  Flask==1.1.1
gunicorn==19.9.0
itsdangerous==1.1.0
Jinja2==2.10.1
MarkupSafe==1.1.1
Werkzeug==0.15.5
numpy>=1.9.2
scipy>=0.15.1
scikit-learn>=0.18
matplotlib>=1.4.3
pandas>=0.19

```
## Deployment

To deploy this project on [render](https://dashboard.render.com/)

```bash
  npm run gunicorn app:app
```


## Demo

Below is the domo for created application

![rice (1)](https://user-images.githubusercontent.com/109405138/210094280-ded72b7d-801c-4999-8d1c-e0c0f00192d6.gif)


## Live demo
Below is the link for live demo

https://rice-production-analysis-api.onrender.com/


## Learning Objective
The following points were the objective of the project . If you are looking for all the following points in this repo then i have not covered all in this repo. I'm working on blog about this mini project and I'll update the link of blog about all the points in details later . (The main intention was to create an end-to-end ML project.)

- Data gathering
- Descriptive Analysis
- Data Visualizations
- Data Preprocessing
- Data Modelling
- Model Evaluation
- Model Deployment
## Technical Aspect
- Using PowerBI dekstop create the report.
- Training a machine learning model using scikit-learn.
- Building and hosting a Flask web app on Render.
- A user has to put details like ram, battry power, Pixel resolution Height etc .
- Once it get all the fields information , the prediction is displayed on a new page .
## Usage/Examples

```javascript
app=Flask(__name__)

@app.route('/')
def page():
    return render_template('index.html')

if __name__=='__main__':
    app.run(debug=True)
```


## Dataset
Now we can download the dataset on Kaggle and make analysis for it. Kaggle is the one of the largest website have to provide the datasets on verious domain.
In the more information about the Kaggle plese [Click Here](https://www.kaggle.com/)

Below link is to dataset on kaggle

https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification
## Acknowledgements

 - [Awesome HTML Templates](https://github.com/Ganeshdhanawade/Rice-Production-Analysis)
 - [Awesome Flask file](https://github.com/Ganeshdhanawade/Rice-Production-Analysis/blob/main/app.py)


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

`ANOTHER_API_KEY`


## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
    
## Lessons Learned

Now the bulding that project i can learn the concept of how to create the web in HTML and how to desing that page well attractive. Also i can get the knowlaged about the render to how exactly deploy the model on cloud.

In challanges my mesure challange is that how to select the best feature they are highly affected my responce.
and selection of the best model to improve the accuracy.


# Hi, I'm Ganesh! 👋


## 🚀 About Me
I am Completed post graduation in statistics with verious takenincal skills and 2+ year of experiance in data science domain. This project i create on self learning.


## Other Common Github Profile Sections
👩‍💻 I'm currently working on Assistant Proffesor in KVM,wai

🧠 I'm currently learning Deep learning and NLP.

👯‍♀️ I'm looking to Job Change toword the data science.




## 🛠 Skills
R, spss, Python, Flask, ML, DL, NLP, Render, MySQL, PowerBI, Excel etc.


![Logo](https://camo.githubusercontent.com/3cdf9577401a2c7dceac655bbd37fb2f3ee273a457bf1f2169c602fb80ca56f8/68747470733a2f2f666f7274686562616467652e636f6d2f696d616765732f6261646765732f6d6164652d776974682d707974686f6e2e737667)
![images](https://user-images.githubusercontent.com/109405138/209291383-14f3f225-e593-4b1b-a506-54db907bb433.png)
![download](https://user-images.githubusercontent.com/109405138/209292205-98d13147-5a84-47d3-82eb-870197067abf.png)


## Feedback

If you have any feedback, please reach out to us at dhanawadeganesh386@gmail.com


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Ganeshdhanawade/Data-Science-Portfolio)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ganesh-dhanawade-47653b201?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BzQkwQvdBRCyb0AhsyHF%2BdQ%3D%3D)


