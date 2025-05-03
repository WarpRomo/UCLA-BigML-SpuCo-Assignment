# UCLA-BigML-SpuCo-Assignment
### This contains the code for the sample SpuCo assignment, which involves training an accurate model on an MNIST dataset that contains spurious features, such as specific background colors amongst certain classes.

# Video Explanation
### Explanation of the code and methods can be found here:
### https://www.youtube.com/watch?v=faLSrMWbSXU
### [![Youtube Video](https://img.youtube.com/vi/faLSrMWbSXU/0.jpg)](https://www.youtube.com/watch?v=faLSrMWbSXU)

# Results
### The model that was trained using the George Method and its sampling performed much better in the evaluation than the model which was trained with no particular sampling.
### The original model only performs well on images with the spurious feature (background color)
### ![image](https://github.com/user-attachments/assets/2d3ba713-2071-4954-a9dd-0433500f4235)
### However the model which was trained with group balanced sampling performed well across all kinds of images, indicating it properly learnt to identify the numbers / classes.
### ![image](https://github.com/user-attachments/assets/2a6e2d8c-7fcc-4d49-818a-2f6079270c3b)

#### By Ritik Jalisatgi, ritik@ucla.edu, along with help from SpuCo quickstart code
#### https://github.com/BigML-CS-UCLA/SpuCo/tree/master/quickstart
