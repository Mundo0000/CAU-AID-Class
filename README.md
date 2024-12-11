# Usage
1. Run the script:
```bash
pyhton knn_iris_classifier.py
```
3. Enter the number of neighbors(`k`) when prompted.
4. View the model's accuracy and balanced accuracy in the console.
5. input sepal.length and petal.length in the format value1,value2 to predict the iris species.

# Example
## Console Interaction:
```bash
Enter the number of neighbors (k) for KNN: 3
Model Accuracy: 0.96
Balanced Accuracy: 0.95
Enter the sepal.length and petal.length for the iris in the format 'sepal_length,petal_length':5.1,1.8
predicted Label: Virginica
```
# Note
- Ensure that the input for predictions is numeric and follows the correct format(`value1,value2).
- Modify the dataset loading path in the script if necessary.

# License
This project is licensed undert the MIT License.

## Author
Developed by DoHyun Mun
