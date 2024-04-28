
# Email Spam Classifier: Spam Prediction and Model Comparison

## Description
This project aims to classify emails as spam or ham using machine learning algorithms. The dataset comprises around 5.5 thousand training emails in .txt format, labeled as spam or ham in the filenames. The project compares machine learning models such as: 

- Naive Bayes

- Decision Tree

- Random Forest

- Support Vector Machine (SVM)
  
For predicting spam emails, a normal Naive Bayes model is trained and used. For comparing different models, hyperparameter tuning is performed on each model, including Naive Bayes. Additionally, a bagging ensemble model is implemented to further increase accuracy.


## How to Run the ipynb File

You can run the project in various environments:
- Use Jupyter Notebook
- Install Anaconda distribution
- Run it on Kaggle or Google Colab

Ensure you have the following Python libraries installed:
- scikit-learn
- numpy

You can install them using pip:
```bash
pip install scikit-learn numpy
```

## Significance of the Project

### Predicting Spam Email
In cell 9 of the Jupyter notebook, you can input an email text using the new_email variable. A normal Naive Bayes model is trained to predict whether the email is spam or ham.

### Model Comparison
After preprocessing and preparing the training dataset, hyperparameter tuning is performed for all algorithms, including Naive Bayes, Decision Tree, Random Forest, and SVM. The notebook outputs the improved accuracies of all models after hyperparameter tuning. Additionally, a bagging ensemble model is employed to further increase accuracy.

## Tests

A spam email example:\
Congratulations! You've won a free cruise to the Caribbean. Click here to claim your prize now!

A non spam email example:\
Hi John,

I hope this email finds you well. I wanted to follow up on our conversation from yesterday regarding the upcoming project deadline. 

Please let me know if you need any further information or assistance.

Best regards,\
Dipanjan

\
To test the project, you can use any exemplary spam email text like the above given and input in cell 9 of the notebook after which it will predict whether the email is spam or ham.

## Reference

- Sharma, Priti, and Uma Bhardwaj. "Machine Learning based Spam E-Mail Detection." International Journal of Intelligent Engineering & Systems 11.3 (2018).

- Kumar, Nikhil, and Sanket Sonowal. "Email spam detection using machine learning algorithms." 2020 Second International Conference on Inventive Research in Computing Applications (ICIRCA). IEEE, 2020.


## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License


## 🚀 About Me
I'm Dipanjan Karmaker Amit. I'm an undergraduate final year student of RUET(Rajshahi University of Engineering and Technology).

You can find me on GitHub at [DipanjanAmitRS](https://github.com/DipanjanAmitRS).

