# LSTM-Text-generation

Main concept of our project was to deliver generated text on the basis of previously created text by Leo Tolstoy. 

We have taken LSTM Recurrent Neural Networks in order to use them as generative models. Our goal was to not use them only as predictive models but what is more they learn the sequences of a problem and then generate entirely new text.

During our project we have discovered how to create a generative model for text, with the usage of LSTM recurrent neural networks in Python with Keras. 

Step by step:
1. Choosing the text - https://www.gutenberg.org/files/2600/2600-0.txt
2. Preparation of the text- modification of the txt in order the model could work
![](https://user-images.githubusercontent.com/61584933/82455348-2479b180-9ab3-11ea-889a-7bcd223f9bff.png)
3. Division of text into small batches (40 characters each)
![](https://user-images.githubusercontent.com/61584933/82455687-81756780-9ab3-11ea-8292-abf51447c021.png)
4. Vectorization of the batches
![](https://user-images.githubusercontent.com/61584933/82455742-9a7e1880-9ab3-11ea-9aff-f2a0b54fe928.png)
5. LSTM Model creation
![](https://user-images.githubusercontent.com/61584933/82455843-bbdf0480-9ab3-11ea-9c24-d30e361ae565.png)
6. Fitting the model based on vectorised characters and printing the output using callback function
![](https://user-images.githubusercontent.com/61584933/82455878-cac5b700-9ab3-11ea-9bdf-4fd27695f22e.png)
![](https://user-images.githubusercontent.com/61584933/82455930-dd3ff080-9ab3-11ea-8857-66b306f6ec48.png)
![](https://user-images.githubusercontent.com/61584933/82455999-ef219380-9ab3-11ea-9c62-45416534ab3e.png)
![](https://user-images.githubusercontent.com/61584933/82456047-fe084600-9ab3-11ea-928d-7952db48b783.png)


Code comes of a course T81-558: Applications of Deep Neural Networks by Jeff Heaton
https://github.com/jeffheaton/t81_558_deep_learning/blob/master/t81_558_class_10_3_text_generation.ipynb
