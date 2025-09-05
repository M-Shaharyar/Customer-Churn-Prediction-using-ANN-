<h1>Customer Churn Prediction using ANN</h1>

<p>This project implements an <b>Artificial Neural Network (ANN)</b> to predict customer churn 
(whether a customer will leave the bank or not) based on historical data. 
The model is built in Python using <b>TensorFlow/Keras</b> and trained on the <b>Churn Modelling dataset</b>.</p>

<h2>📌 Project Overview</h2>
<p>Customer churn is a major concern for businesses, as retaining existing customers 
is often more cost-effective than acquiring new ones.</p>
<ul>
<li>Preprocesses the dataset (handling categorical variables, scaling features).</li>
<li>Trains an ANN model to classify customers into <b>Churn</b> or <b>Not Churn</b>.</li>
<li>Evaluates the model’s performance using accuracy and loss curves.</li>
</ul>

<h2>🗂 Dataset</h2>
<p>The dataset used is <b>Churn_Modelling.csv</b>, which contains customer information such as:</p>
<ul>
<li>Customer demographics (Age, Gender, Geography)</li>
<li>Bank account details (Balance, Tenure, Credit Score)</li>
<li>Customer activity (Number of products, Has credit card, Is active member)</li>
<li>Target variable: <code>Exited</code> (1 = churn, 0 = not churn)</li>
</ul>

<h2>⚙️ Tech Stack</h2>
<ul>
<li><b>Python 3</b></li>
<li><b>Pandas, NumPy</b> → Data preprocessing</li>
<li><b>Matplotlib</b> → Visualization</li>
<li><b>TensorFlow / Keras</b> → Deep Learning (ANN model)</li>
</ul>

<h2>🚀 How to Run</h2>
<ol>
<li>Clone the repository:
<pre><code>git clone https://github.com/M-Shaharyar/customer-churn-prediction-ann.git
cd customer-churn-prediction-ann</code></pre></li>

<li>Run Jupyter Notebook:
<pre><code>jupyter notebook customer-churn-prediction-using-ann.ipynb</code></pre></li>
</ol>

<h2>📊 Model Architecture</h2>
<ul>
<li><b>Input Layer</b>: 11 features after preprocessing</li>
<li><b>Hidden Layers</b>: Dense layers with ReLU activation</li>
<li><b>Output Layer</b>: Sigmoid activation (binary classification)</li>
</ul>

<h2>📈 Results</h2>
<ul>
<li>Training and validation accuracy/loss curves plotted</li>
<li>Achieved high accuracy in predicting churn vs. non-churn customers</li>
</ul>

<h2>📌 Future Improvements</h2>
<ul>
<li>Hyperparameter tuning (learning rate, number of layers/neurons)</li>
<li>Try different architectures (DNN, CNN, RNN)</li>
</ul>

<h2>🤝 Contributing</h2>
<p>Feel free to fork this repo, open issues, and submit pull requests to improve the project.</p>

<h2>📜 License</h2>
<p>This project is licensed under the <b>MIT License</b>.</p>
