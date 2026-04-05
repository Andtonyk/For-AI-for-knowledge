# For-AI-for-knowledge
AI_course_colab

The oriantation exercise also included some questions, that needed to be researched and answered in one's own words. Listed below were my findings.

## Is Shaoe Printing Possible?
 The provided material on https://scikit-learn.org/stable/api/index.html did seem to side with the answer being: yes, it is possible to use the provided data set to get shapes out of the data.
 An example of this is the one used in a later part of the same material. The code used to verify this was the same as in the material: print(digits.data.shape) (1797, 64) import matplotlib.pyplot as plt plt.matshow(digits.images[0], cmap="gray") plt.show()

 This code was inserted into onto the section at the beginning of the provided code
 
from sklearn import datasets
# this is a comment
digits = datasets.load_digits()
print(digits.data.shape)
(1797, 64)
import matplotlib.pyplot as plt
plt.matshow(digits.images[0], cmap="gray")
plt.show()

As you can see, the original part of the "print(digits.data)" was the only part of the original code to be changed, and since the effects were a graphical view, I would thus conclude that the method works as a graphical output option. 

## The (hopefully) accurate and understandable information of the used dataset

The digits dataset is in accordance with it's descriptor a copy of an already existing dataset (UCI ML hand-written digits dataset).

The information regarding the data set has been copied from the dataset's description for maximum accuracy.

    Classes: 10
    Samples per class: 180
    Samples total: 1797
    Dimensionality: 64
    Features: Integers 0 - 16

Link to the original dataset: https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits
Link to the description of the digits dataset: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html#sklearn.datasets.load_digits

n text (Markdown), describe the digits data set. Where does it come from? How many instances and classes does it have? Etc.
