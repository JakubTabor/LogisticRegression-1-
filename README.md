# LogisticRegression-1
# First i plot my data to see how it is placed """plt.scatter(df.age, df.bought_insurance, marker='+', color='red')"""
# Then i split my data into "train" and "test", i esparate column "age" from "bought_insurance"
# Next i import my "LogisticRegression" model and train my data """model.fit(X_train, y_train)"""
# I get my "y_pred" """model.predict(X_test)""" and "score" also I check probability """model.predict_proba(X_test)"""
# Using my "coef." and "intercept", I write function "sigmoid" that contain this pattern """1 / (1 + math.exp(-x))"""
# And create another function "prediction_function" that contain pattern to calculate probalility using "coef" and "intercept" """0.123 * age - 4.72"""
# As "y" i use my "sigmoid" function """sigmoid(z)""" and "z" is my pattern
