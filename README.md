# opensource-final-project
# purpose of this project
-this project is for classifing the pictures of tumor by machine learning 

# why did i use svm
-I have learned dicision tree and randomforest in this semester, so i made model by using Random forest in 1R. but the accuracy was 0.62. i started finding new model, i choose supper vector machine.

# code comment
model=SVC(random_state=100,C=5,gamma=10)
-create model with Suppert vector machine and chage parameter.
model.fit(X_train,y_train)
-fit the model with train set.

# features
-my model's feature is parameter. i suppose that each tumor has strong characteristic. And i found that most important parameter in svm model is c and gamma. so i conclude that although upper c and gamma make somehow overfitting, model will work well because of each strong characteristic. after some try, i decide c=5, gamma=10, randomstate=100(this is given value by professor) 
