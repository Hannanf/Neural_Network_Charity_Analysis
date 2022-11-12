
<h2>Module 19 - Creating a Neural Network Model and trying to Optimize the Model using Various Metrics 
  </h2>
  
______________________________________________________________________
<h4>OVERVIEW OF MODULE 
</h4>

______________________________________________________________________
This module consisted of 3 main parts which included the following 
<br>
<br>1) Pre-processing data from .csv file so it may be used most efficiently in our neural network model 
<br>2) using the data from 1) to create compile, train, and evaluate the model 
<br>3) Trying to optimize the model 

______________________________________________________________________
<h4>Results 
</h4>
______________________________________________________________________
<br>Data Preprocessing
<br>
<br>1) "IS_SUCCESSFUL" column is used as the target column
<br>2) All columns except "IS_SUCCESSFUL" can be used as input variables for the model 
<br>3) columns/variables which do not have any baring or impact on the target column ("IS_SUCCESSFUL") were dropped. These included "EIN", and "NAME"
<br>
<br>
<br>Compiling, Training, and Evaluating the Model

<br>4) As seen in Figure 1, I chose 5 layers. First with 50 neurone, second with 40 neurone, third with 30 neurone, fourth with 20 neurons and fifth with 10 neurons. I selected Softmax for my activation function
<br>5) Unfortunately, I was not able to reach the target performance 
<br>6) As seen in figure 1 and 2, I added additional layers, I dropped additional rows, and I added more hidden layers 

![image](https://user-images.githubusercontent.com/103878061/201490787-11fe2d59-a121-4bec-bcca-83f1a500dd4e.png)

Figure 1: Testing different number of layers, nodes, and activation functions to get the most accurate model 

![image](https://user-images.githubusercontent.com/103878061/201490794-b0cd5825-2316-47ef-a34f-0ea8c6fb2b26.png)

Figure 2: Dropping additional columns to try and get the most accurate model 
______________________________________________________________________
<h4>Summary 
</h4>
______________________________________________________________________

As seen in figure 3, I was able to reach an accuracy of 53%. Although I was not able to reach the desired accuracy, changing metrics on the model was a great learning opportunity to better understand how the model works. In the future I would spend more time and additional data analysis techniques to determine which input variables effect the output. I would also try to collect more data and using varying epochs, activation functions, hidden layers, and nodes to optimize the model 

![image](https://user-images.githubusercontent.com/103878061/201490805-af0310ee-1cfe-40ed-9bf4-6ea2411a833c.png)

Figure 3: results of the model showing the loss and accuracy 
