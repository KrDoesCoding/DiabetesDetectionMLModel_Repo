<h1>Diabetes Detection Model using AI, Machine Learning and Neural Networks</h1>

<h2>Overview</h2>
<p>
  This is an advanced machine learning tool designed to predict the risk of diabetes based on several health-related features, such as blood glucose levels, BMI, and more. Using a deep neural network with multiple layers and K-Fold cross-validation, this model aims to provide reliable and accurate predictions for diabetes risk, assisting healthcare professionals in early diagnosis and prevention.
</p>

<h2>Features</h2>
<ul>
  <li><strong>Data Preprocessing:</strong> Standardizes features using <em>StandardScaler</em> to ensure the data is normalized.</li>
  <li><strong>Neural Network Architecture:</strong> Consists of six layers, including dropout for regularization and ReLU activation functions.</li>
  <li><strong>K-Fold Cross-Validation:</strong> Model is trained using 5-fold cross-validation to improve the robustness of the predictions.</li>
  <li><strong>Performance Metrics:</strong> The model evaluates accuracy, precision, recall, and F1 score to provide a comprehensive view of the performance.</li>
  <li><strong>Loss Curve Visualization:</strong> Plots the loss curve over the epochs to monitor training progress.</li>
  <li><strong>Model Save and Load:</strong> Trained model can be saved and loaded for future predictions.</li>
</ul>

<h2>Model Architecture</h2>
<p>
  The model consists of a deep neural network with the following architecture:
</p>
<ul>
  <li><strong>Input Layer:</strong> 8 features (blood glucose, BMI, age, etc.)</li>
  <li><strong>Hidden Layers:</strong>
    <ul>
      <li>First Layer: 64 neurons with ReLU activation</li>
      <li>Second Layer: 128 neurons with ReLU activation</li>
      <li>Third Layer: 256 neurons with ReLU activation</li>
      <li>Fourth Layer: 128 neurons with ReLU activation</li>
      <li>Fifth Layer: 64 neurons with ReLU activation</li>
      <li>Dropout with a 0.3 probability to prevent overfitting</li>
    </ul>
  </li>
  <li><strong>Output Layer:</strong> A single neuron with sigmoid activation for binary classification (diabetes risk: 1 = yes, 0 = no).</li>
</ul>

<h2>Training</h2>
<ul>
  <li>Batch size: 64</li>
  <li>Number of epochs: 100</li>
  <li>Optimizer: Adam optimizer with a learning rate of 0.001</li>
  <li>Loss Function: Binary Cross Entropy Loss with Logits</li>
</ul>

<h2>Results</h2>
<p>After 100 epochs of training, the model achieves an accuracy of approximately <strong>91%</strong> on the test data, making it a reliable tool for predicting and detecting diabetes.
</ul>

