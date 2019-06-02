import matplotlib.pyplot as plt
from sklearn import datasets
from sklearn.neural_network import MLPClassifier
from sklearn.metrics import classification_report,confusion_matrix

# import some data to play with
iris = datasets.load_iris()
X = iris.data[:, :30]  # we only take the first two features.
Y = iris.target
#print X.shape
#print Y.shape


clf = MLPClassifier(hidden_layer_sizes=(30,30,30),solver='adam',learning_rate_init=0.01, max_iter=300)
r = clf.fit(X,Y)
#print r

#print (clf.coefs_)

prediction = clf.predict(X)
print (confusion_matrix(Y,prediction))
print classification_report(Y, prediction)
print prediction

 #Plot the tra ining points
plt.scatter(X[:, 0], X[:, 1], c=Y, cmap=plt.cm.Paired)
plt.xlabel('Sepal length')
plt.ylabel('Sepal width')
plt.show()
