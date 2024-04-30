# Bank Turnover Prediction Using ANN
- We will build a deep learning model to predict the churn and use precision,recall, f1-score to measure performance of our model

## What is its usecase?
- Bank turnover prediction, also known as customer churn prediction,  using Artificial Neural Networks (ANNs) has several valuable use cases for banks. Here are some of the key benefits:

    - **Reduced Customer Churn**: By accurately predicting which customers are at a high risk of leaving the bank,  banks can take proactive steps to retain them. This might involve offering personalized incentives, improving customer service interactions, or addressing specific concerns before a customer decides to churn.

    - **Targeted Marketing Campaigns**: ANNs can help banks identify customer segments with a higher churn probability. This allows for targeted marketing campaigns focused on retaining these at-risk customers.  These campaigns can be more effective and cost-efficient compared to generic marketing efforts.

    - **Improved Product Development**:  Understanding customer churn behavior can help banks develop products and services that better meet customer needs and preferences.  Analyzing churn data through ANNs can reveal patterns and trends that wouldn't be readily apparent with traditional methods. This can inform the creation of new features or targeted product offerings to retain specific customer segments.

    - **Risk Management**:  Churn can have a significant financial impact on a bank. By predicting churn, banks can identify customers who are more likely to default on loans or credit cards. This allows for better risk management strategies, such as adjusting credit limits or offering loan restructuring options.

    - **Resource Allocation**:  ANNs can help banks optimize resource allocation by directing customer service efforts towards at-risk customers. This ensures that valuable resources are focused on retaining valuable customers who might otherwise churn.

    - **Improved Customer Experience**:  By understanding the reasons behind churn, banks can improve the overall customer experience. This can involve streamlining processes, enhancing digital banking functionalities, or providing personalized support to address customer pain points.

## Data Description
 - I have used the `Churn-Modelling.csv` file for the project
 - The dataset contains information like:
  0. RowNumber         
  1. CustomerId        
  2. Surname         
  3. CreditScore       
  4. Geography       
  5. Gender          
  6. Age               
  7. Tenure            
  8. Balance          
  9. NumOfProducts     
  10. HasCrCard         
  11. IsActiveMember    
  12. EstimatedSalary  
  13. Exited   


## Libraries Used
 - Numpy
 - Pandas
 - Matplotlib
 - Seaborn
 - Scikit-learn
 - TensorFlow
 - Keras

## Evaluation Metrics for the Imbalanced Data
 - Accuracy: 0.86  (86%)
 - f1-score for class '0': 0.92 (92%)
 - f1-score for class '1': 0.46 (46%)

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: `git clone https://github.com/NebeyouMusie/Bank-Turnover-Prediction-Using-ANN.git`
 3. Create and Activate Virtual Environment (Recommended)
    - `python -m venv venv`
    - `source venv/bin/activate`
 4. Install Libraries: `pip install numpy pandas matplotlib seaborn scikit-learn tensorflow`
 5. Open `bank-turnover.ipynb` and run all cells
 6. Or you can download the `Churn_Modelling.csv` and `bank-turnover.ipynb` file from the repository, upload those files to [Google Colab](https://colab.research.google.com/) then run all the cells in the `bank-turnover.ipynb` Notebook

## Acknowledgments
 - I would like to thank [codebasics](https://youtube.com/@codebasics?si=S9xKOK9Hztsu2-Oi)

## Contact
 - LinkedIn: [Nebeyou Musie](https://www.linkedin.com/in/nebeyou-musie)
 - Gmail: nebeyoumusie@gmail.com
 - Telegram: [Nebeyou Musie](https://t.me/NebeyouMusie)
    

