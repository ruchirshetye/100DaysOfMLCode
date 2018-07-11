# Building an Artificial Neural Net using Keras library.

Our aim : Predicting whether the customer will leave a particular bank or not.

***Step 1: Data Pre-processing***
          
  1) Importing dataset 
  Here we are using Churn_Modelling.csv which has data of customers in a bank.
  ```
  dataset = pd.read_csv('Churn_Modelling.csv')
  ```
  2) Splitting into Independant variable(x) and Dependant variable(y).
  
  3) Encoding categorical data. Importing encoding libraries.
  ```
  from sklearn.preprocessing import LabelEncoder, OneHotEncoder
  ```
  4) Splitting the dataset into the Training set and Test set.</br>
     Here we are consodering 80:20 split between the training set and test set respectively.
     
  5) Feature Scaling </br>
     Yes! It's essential in neural networks. 
 ```
  from sklearn.preprocessing import StandardScaler
  sc = StandardScaler()
  X_train = sc.fit_transform(X_train)
  X_test = sc.transform(X_test)
```
  ***Step 2: Let build an ANN***
  
  1) Importing keras
   ```
  import keras
  from keras.models import Sequential #Helps you build the NN
  from keras.layers import Dense # Takes care of randomly initialized weights
  ```
  2) Intialising ANN.</br>
  Here we initialise ANN as sequence of layers.</br>
   ```
   classifier = Sequential() # Classifier 
   ```
  3)Defining the layers. </br></br>
   
  - Here we have used activation function 'relu'. relu is considered as the one of the best activation function based on experiments.</br> 
  - Parameter ***'init'*** is used to declare the random initialization function which we are goin to use.</br>
  - Parameter ***'input_dim'*** stores the number of input nodes in the neural network.</br>
  - Parameter ***'output_dim'*** used to store the hidden layer node. No. of hidden nodes depends from scenario.</br>
  - There's a simple formula for calculating hidden layer which is ***(input_node + output_node)/2.***  </br>
      ```
    
      classifier.add(Dense(output_dim = 6, init= 'uniform' , activation = 'relu', input_dim = 11 ))
      ```
    </br>
  - Now we add the middle layer i.e the hidden layer. 
  
      ```
      classifier.add(Dense(output_dim = 6, init= 'uniform' , activation = 'relu' ))
      ```
  - Then adding the output layer with one node.</br>
  - Here we use the activation function 'sigmoid' so that we can get the probability of the customer leaving the bank.  

     ```
     classifier.add(Dense(output_dim = 1, init= 'uniform' , activation = 'sigmoid' ))
     ```
  4) Compiling ANN. </br></br>
    To calculate loss we initially used 'Sum of Squared diffrences' method in Linear Reggression.</br>
    Here we have to use Logarithmic Loss on which our Stochastic Gradient Descent Algo is based.</br>
    Since y has binary output we have used ***loss = 'binary_crossentropy'*** . If y had more than two output then ***loss = 'categorical_crossentropy'*** 
     ```
     classifier.compile(optimizer = 'adam' ,loss = 'binary_crossentropy', metrics = ['accuracy'] )
     ```
