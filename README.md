<div align='center'>
  

  <h1>Diabetes Prediction using Machine Learning</h1>

  <p>
This project uses machine learning algorithms to predict the likelihood of a patient having diabetes based on certain diagnostic criteria. The dataset used in this project contains information about various diagnostic measurements for patients, such as glucose, blood pressure, insulin level, etc.

The aim of this project is to build and compare the performance of different machine learning models - K-Nearest Neighbors, Logistic Regression, Decision Tree, Random Forest, Support Vector Machine - to accurately predict the presence of diabetes in patients.
  </p>
  

<!-- Badges -->


 


<!-- Table of Contents -->

## :notebook_with_decorative_cover: Table of Contents

- [Dataset](#signal_strength-dataset)
- [Dependencies](#toolbox-dependecies)
- [Installation](#gear-installation)
- [Usage](#play_or_pause_button-usage)
- [Results](#rocket-results)
- [Conclusion](#construction-conclusion)
- [Deployment](#triangular_flag_on_post-deployment)
- [License](#balance_scale-license)
- [Contact](#handshake-contact)



## :signal_strength: Dataset

The dataset used in this project is the Pima Indians Diabetes Dataset, which can be found here. The dataset consists of 768 samples with 8 features, including the target variable, indicating the presence of diabetes. The dataset can be found on [`Kaggle`](https://www.kaggle.com/datasets/mathchi/diabetes-data-set). It includes following health criteria:

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (years)
- Outcome: Class variable (0 or 1)

### Details
- Number of Instances: 768
- Number of Attributes: 8 plus class
- Missing Attribute Values: Yes
- Class Distribution: (class value 1 is interpreted as "tested positive for diabetes")



## :toolbox: Dependecies

`python 3.8.3`

`pandas`

`numpy`

`sklearn`

`matplotlib`

`seaborn`

`pickle`



## :gear: Installation

Clone the repository and install the required dependencies using the following commands:

```bash
git clone https://github.com/Aakashsharma614/Diabetes-Pred
```

```bash
cd Diabetes-Prediction
```



## :play_or_pause_button: Usage

The Jupyter notebook Diabetes Prediction.ipynb contains the code for loading and preprocessing the dataset, as well as implementing and evaluating the KNN, Logistic Regression, Random Forest, Support Vector Machine and Decision Tree models. To run the notebook, simply open it in Jupyter and run each cell in order.
<br/>


## : Images Related:

<img width="654" alt="diabetes1" src="https://github.com/user-attachments/assets/f802c63c-17dd-4f4b-84cd-bce38dbd7ca3" />



<img width="404" alt="Screenshot 2025-05-22 225801" src="https://github.com/user-attachments/assets/493c08f2-b0c7-41af-bb03-65019ecff388" />





## :rocket: Results

<div align='center'>

| Model                                             | Accuracy |
|---------------------------------------------------|----------|
| K-Nearest Neighbour                               | 79.22%    |
| Logistic Regression                               | 81.82%    |
| Random Forest                                     | 79.22%    |
| Support Vector Machine                            | 83.12%    |
| Decision Tree                                     | 81.82%    |
| Hypertuning - GridSearchCV on Logistic Regression | 83.12%    |

</div>



## :construction: Conclusion

In this project, we compared the accuracy of five different machine learning models as well as hypertuning parameters for predicting diabetes based on various health criteria. We found that Support Vector Machine was the most accurate model, with an accuracy of 83.12%. The above results also tells that Logistic Regression and Decision Tree are also performing good and hypertuing on Logistic Regression increases its accuracy around 2%. This project could be further improved by testing additional models and/or including additional health criteria in the dataset.



## :triangular_flag_on_post: Deployment

Checkout the deployment repository [`here`]



## :balance_scale: License

This project is licensed under the MIT License - see the 


## :handshake: Contact

![](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)

Your Name - Aakash Sharma
Project Link: (https://github.com/Aakashsharma614/Diabetes-Pred))
<hr />
<br />
<div align="center">Don't forget to leave a star ⭐️</div>
