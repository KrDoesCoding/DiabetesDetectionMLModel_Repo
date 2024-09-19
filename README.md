<h1>Diabetes Detection using Machine Learning and Neural Networks</h1>

<h2>Overview</h2>
<p>
  This is an AI-powered tool designed to predict the likelihood of diabetes based on key health indicators. Using machine learning techniques, the model analyzes features such as age, blood glucose levels, BMI, and more to provide reliable risk predictions. This project aims to assist healthcare professionals in early detection and diagnosis of diabetes, empowering them to take preventive or proactive actions.
</p>

<h2>Features</h2>
<ul>
  <li><strong>Data Preprocessing:</strong> Handles data cleaning, normalization, and feature scaling.</li>
  <li><strong>Neural Network Model:</strong> Utilizes a multi-layered neural network with ReLU activation functions to predict diabetes risk.</li>
  <li><strong>Binary Classification:</strong> Predicts whether a patient is at risk of diabetes (1) or not (0).</li>
  <li><strong>Accuracy Optimization:</strong> Adjustable hyperparameters and model architecture to fine-tune performance.</li>
  <li><strong>Batch Training:</strong> Trains the model in batches for efficient use of resources and memory.</li>
  <li><strong>Performance Evaluation:</strong> Measures model accuracy and performance using a test dataset.</li>
</ul>

<h2>Model Architecture</h2>
<p>The model is a simple neural network composed of:</p>
<ul>
  <li><strong>Input Layer:</strong> 8 features</li>
  <li><strong>Two Hidden Layers:</strong>
    <ul>
      <li>First hidden layer with 20 neurons.</li>
      <li>Second hidden layer with 40 neurons, both using ReLU activation.</li>
    </ul>
  </li>
  <li><strong>Output Layer:</strong> A single neuron with sigmoid activation to predict the probability of diabetes.</li>
</ul>

<h2>Results</h2>
<p>
  After 100 epochs of training, the model achieves an accuracy of approximately <strong>85%</strong> on the test data, making it a reliable tool for predicting diabetes risk.
</p>
