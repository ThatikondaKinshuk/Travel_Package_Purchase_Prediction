**Problem Statement - Travel Package Purchase Prediction**
**Objective**

Predict which customer is more likely to purchase the newly introduced travel package.

**Data Dictionary**

**Customer details:**

**CustomerID:** Unique customer ID
**ProdTaken:** Whether the customer has purchased a package or not (0: No, 1: Yes)
**Age:** Age of customer
**TypeofContact:** How customer was contacted (Company Invited or Self Inquiry)
**CityTier:** City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e. Tier 1 > Tier 2 > Tier 3. It's the city the customer lives in.
**Occupation:** Occupation of customer
**Gender:** Gender of customer
**NumberOfPersonVisiting:** Total number of persons planning to take the trip with the customer
**PreferredPropertyStar:** Preferred hotel property rating by customer
**MaritalStatus:** Marital status of customer
**NumberOfTrips:** Average number of trips in a year by customer
**Passport:** The customer has a passport or not (0: No, 1: Yes)
**OwnCar:** Whether the customers own a car or not (0: No, 1: Yes)
**NumberOfChildrenVisiting:** Total number of children age less than 5 planning to take the trip with the customer
**Designation:** Designation of the customer in the current organization
**MonthlyIncome:** Gross monthly income of the customer]

**Customer interaction data:** 

**PitchSatisfactionScore:** Sales pitch satisfaction score
**ProductPitched:** Product pitched by the salesperson
**NumberOfFollowups:** Total number of follow-ups has been done by the salesperson after the sales pitch
**DurationOfPitch:** Duration of the pitch by a salesperson to the customer

**Travel Package Purchase Prediction**

**Overview**

This project focuses on predicting the likelihood of a customer purchasing a travel package based on various features. By utilizing machine learning techniques, we aim to assist travel agencies in targeting potential customers more effectively and optimizing their marketing strategies.

**Table of Contents**

- [Background](#background)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

**Background**

Understanding customer behavior is crucial for businesses in the travel industry. This predictive model can help travel agencies identify potential customers who are more likely to purchase travel packages, allowing for targeted marketing efforts and improved conversion rates.

**Installation**

1. Clone the repository:
   ```bash
   !git clone https://github.com/ThatikondaKinshuk/Travel_Package_Purchase_Prediction.git
   !cd travel-package-purchase-prediction

2. Install the required dependencies:
   ```bash
   !pip install -r requirements.txt

**Usage**
1. Preprocess the data:
   ```bash
   !python preprocess.py

3. Train the model:
   ```bash
   !python train_model.py

5. Make Predictions:
   ```bash
   !python predict.py

**Data**
The dataset used for this project is available in the data directory. It includes features such as customer demographics, past travel history, and other relevant information.

**Model Training**
The model is trained using the train_model.py script, which utilizes machine learning algorithms to learn patterns from the training data.

**Evaluation**
Model performance is evaluated using metrics such as accuracy, precision, recall, and F1 score. The evaluation results are printed and saved for further analysis.

**Results**
The results of the model predictions can be found in the results directory. Visualization and analysis of the results are provided in the analysis folder.

**Contributing**
Feel free to contribute to the project by opening issues or submitting pull requests. Your input is valuable, and collaboration is encouraged!
