# excel-net
A basic neural net implementation in Microsoft Excel (done ironically). Seriously, don't use this repo I beg you.  

But... if you are curious... here is how you can run a super simple perceptron in excel. You will find this useful if:  
1) You are unfamiliar with programming, but want to see an implementation of a neural net done in software you understand (Excel)  
2) You are familiar with programming, and want to see an implementation of a neural net in the worst way possible.  

# What are neural nets?
Neural nets are a type of "universal function approximator", meaning that it can be fit to output anything given any input. I recommend looking here for more information: http://neuralnetworksanddeeplearning.com/index.html


# Description and instructions
The model learns a function of one variable, with a single hidden layer with tanh activation, and a single output layer with linear activation. To use it, download the excel file and open it.

## Step 1
Type in your activation function into the "output" column. Then drag down the formula to apply to all outputs (there are around 200 of them)
![Step 1](https://github.com/AustinT/excel-net/blob/master/step%201.PNG)

## Step 2
Press the "Reset Random Cells" button to reset the cells to random initializations (using uniform initialization because excel is dumb)
![Step 2](https://github.com/AustinT/excel-net/blob/master/step%202.PNG)

## Step 3
Click on cell D6 and open up the solver menu, located under data. Ensure the cells to manipulate are set correctly (as shown below), then press solve. (the text should read `$G$7:$N$7,$Q$7:$X$7,$AB$9:$AB$16,$AC$9`)
![Step 3](https://github.com/AustinT/excel-net/blob/master/step%203.PNG)

## Step 4
View the results of the learning on the graph (note: it won't always be this good)
![Step 4](https://github.com/AustinT/excel-net/blob/master/step%204.PNG)
