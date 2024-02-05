## Report
<h1>Overview</h1>
<b>The aim of this challenge was to use a given CSV received from 'Alphabet Soup' containing data from over 34,000 organisations and create a binary classifier that could predict whether applicants will be successful if funded by Alphabet Soup.</b>

<h1>Results</h1>
  
<h2>Data preprocessing</h2>
<b>
<ul>
  <li>The target for the model (y) was the 'IS-SUCCESSFUL' column of the dataset, which has a binary answer to if the money was used effectively</li>
  <li>The features for the model (X) was everything else in the dataset with the aforementioned target column dropped </li>
  <li>Unnecessary columns included the organisation names and identification numbers and were dropped from the dataset so as not to affect the model's performance</li>
</ul>
</b>

<h2>Compiling, Training, and Evaluating the Model</h2>
<b>
<ul>
  <li>The number of neurons for each hidden layer was doubled to 32 per layer and two more hidden layers were added for optimisation (making it a total of 4 hidden layers). Better proportionality of neurons with appropriate number of hidden layers result in higher accuracy. </li>
  <li>However, despite four attempts at optimisation, the target model performance was not able to be achieved, despite the accuracy being marginally higher. </li>
  <li>There were a total of four attempts made to improve optimisation</li>
  <ul>
    <li>One less column was dropped (the column with the identification number of the organisation)</li>
    <li>The units of each hidden layer was doubled to 32 per layer</li>
    <li>Two more hidden layers were added</li>
    <li>The number of epochs was increased to 120</li>
  </ul>
</ul>
</b>

<h1>Summary</h1>
<b>
Overall, the deep learning model was somewhat accurate at predicting the success of applicants funded by 'Alphabet Soup' but despite numerous attempts to optimise the model, it still achieved a maximum accuracy of 72.8%. Perhaps further optimisation attempts are required or perhaps another model should be considered.
</b>
