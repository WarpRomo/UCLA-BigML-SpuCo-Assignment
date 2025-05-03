# UCLA-BigML-SpuCo-Assignment
<p>This contains the code for the sample SpuCo assignment, which involves training an accurate model on an MNIST dataset that contains spurious features, such as specific background colors amongst certain classes.</p>

# Video Explanation
<p>Explanation of the code and methods can be found here:<br>
https://www.youtube.com/watch?v=faLSrMWbSXU</p>

# Results
<p>The model that was trained using the George Method and its sampling performed much better in the evaluation than the model which was trained with no particular sampling.
<br>The original model only performs well on images with the spurious feature (background color)</p>
### ![image](https://github.com/user-attachments/assets/2d3ba713-2071-4954-a9dd-0433500f4235)
<p>However the model which was trained with group balanced sampling performed well across all kinds of images, indicating it properly learnt to identify the numbers / classes.</p>
### ![image](https://github.com/user-attachments/assets/2a6e2d8c-7fcc-4d49-818a-2f6079270c3b)

<p>By Ritik Jalisatgi, ritik@ucla.edu, along with help from SpuCo quickstart code<br>
https://github.com/BigML-CS-UCLA/SpuCo/tree/master/quickstart</p>
