# support-vector-machine -algoritm -in-machine-learning
!pip install numpy
import numpy as np
x = np.array([[-1, -1],[-2,-2],[1,1], [2,1]])
y = np.array([1, 1, 2, 2])
from sklearn.svm import SVC
clf = SVC() # support vector classifier
clf.fit(x,y)
print(clf.predict([[-0.8, -1]]))

