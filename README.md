# LogisticRegression-1
# First i plot my data to see how it is placed """plt.scatter(df.age, df.bought_insurance, marker='+', color='red')"""
# Then i split my data into "train" and "test", i esparate column "age" from "bought_insurance"
# Next i import my "LogisticRegression" model and train my data """model.fit(X_train, y_train)"""
# I get my "y_pred" """model.predict(X_test)""" and "score" also I check probability """model.predict_proba(X_test)"""
