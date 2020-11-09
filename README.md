# svm (Support Vector Machine)

- Know as maximum margin hyperplane.
- Apporch is widest margin road.
- Ideas is to find maximum possible distance road.

Note:- In 2 D space, the separating plane is a line.

- The hyperplane is a plane that acts as the decission boundary.
- It can handle Non linear data. because it takes low degree data to high degree data. (Mean 2 D to 3 D)
- Kernal SVM takes data froom low degree to high degree, where data points become linearly separable  and then we draw the plane through the data points.


### Some parameters of SVM:
**- Kernal:** In SKLearn, we can use many kernals such as rbl, poly, sigmoid, linear, precomputed etc.
**- C:** Define the misclassification error of the model. If we take C value high , higher will be penalty of misclassification points and vice-versa.
**- Gamma:** Defines the radius of influance of data points in classification.


#### For multiclass :
1. OVR: One vs Rest.
2. OVO: One vs One.


### Industry application of SVM
- Text Categorization.
- Image Classification
- Bioinformatices (Protein, cancer classification)
- Hand written charcter recognition.


# END
