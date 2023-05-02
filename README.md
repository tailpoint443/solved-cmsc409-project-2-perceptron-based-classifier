Download Link: https://assignmentchef.com/product/solved-cmsc409-project-2-perceptron-based-classifier
<br>
In this assignment you will use the datasets from Project 1. In language of your preference (Python, Java, Matlab, C++), implement a perceptron-based classifier that will iterate until the <strong>total error</strong> is:

<ul>

 <li>Epsilon &lt;10<sup>-5</sup>, for dataset A,</li>

 <li>Epsilon &lt;10<sup>-1</sup>, for dataset B,</li>

 <li>Epsilon &lt;5*10<sup>-1</sup>, for dataset C.</li>

</ul>

To do this, you need to introduce a stopping criterion. You should also introduce a limit on maximum number of iterations (let that be <em>ni</em>=5,000). Normalize the datasets first. Initialize your neuron using random values between (-0.5, 0.5).




Please use unipolar version of:

<ol>

 <li>Hard activation function</li>

 <li>Soft activation function</li>

</ol>




For the scenario <strong>a)</strong> do the following for each of the datasets.

<ol>

 <li>Choose 75% of the data for training, and the rest for testing. Train and test your neuron. Plot the data and decision line for training and testing data (separately). Calculate errors for training and testing dataset.</li>

 <li>Choose 25% of the data for training, and the rest for testing. Train and test your neuron. Plot the data and decision line for training and testing data (separately). Calculate errors for training and testing dataset.</li>

 <li>Compare 1. and 2. Are errors different and if so, why? What is the effect of different data set and effect of different training/testing distributions? When would you use option 1 and when option 2 above? Comment and discuss.</li>

</ol>




Repeat steps 1. through 3. for scenario <strong>b)</strong>.

Important: The data set lists all male and then all female data points. Think about which data points you should use for training and which for testing (i.e. algorithm will fail if trained on one type of patterns and tested on another).

<strong>Pr. 2.2 Soft vs. hard activation function </strong>

Compare and discuss results when hard activation was used vs. when soft activation was used. Comment for each training/testing distribution 1, 2, and 3.


