# Part 1: Neural Network Analysis - Customer Churn Prediction

## 📋 Project Overview

This project implements a comprehensive neural network analysis for predicting customer churn using a structured dataset. The objective is to build, train, and analyze a feed-forward neural network while demonstrating understanding of key concepts like forward pass, loss calculation, backpropagation, and parameter updates.

## 🎯 Objectives

1. **Dataset Understanding**: Explore and analyze the customer churn dataset
2. **Data Preprocessing**: Prepare data for neural network training
3. **Model Building**: Construct a feed-forward neural network
4. **Training & Evaluation**: Train the model and assess performance
5. **Hyperparameter Tuning**: Experiment with different configurations
6. **Reflection**: Analyze neural network learning mechanisms

## 📊 Dataset Information

- **File**: `customer_churn_nn.csv` (located in `../part_1_neural_network_analysis/`)
- **Target Variable**: `churn` (1 = churned, 0 = retained)
- **Total Records**: 2000 customers
- **Features**: 16 input features including:
  - **Categorical**: region, plan_type, contract_type, payment_method
  - **Numerical**: tenure_months, monthly_charges_inr, avg_login_days_per_month, support_tickets_last_90_days, payment_delay_days, data_usage_gb, satisfaction_score, last_complaint_days_ago, discount_percent, autopay_enabled, referral_count

## 🛠️ Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Setup Instructions

1. **Clone or navigate to the project directory**:
   ```bash
   cd part-1-neural-network-analysis
   ```

2. **Create a virtual environment** (recommended):
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

### Running the Jupyter Notebook

1. **Start Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

2. **Open** `notebook.ipynb` in your browser

3. **Run all cells** sequentially to:
   - Load and explore the dataset
   - Preprocess the data
   - Build and train the neural network
   - Evaluate model performance
   - Compare hyperparameter configurations
   - Review analysis and insights

### Notebook Structure

The notebook is organized into the following sections:

1. **Task 1: Dataset Understanding**
   - Data loading and exploration
   - Statistical summary
   - Class distribution analysis
   - Missing value check

2. **Task 2: Data Preprocessing**
   - Handling missing values
   - Categorical encoding (One-Hot Encoding)
   - Feature scaling (StandardScaler)
   - Train-test split (80-20)

3. **Task 3: Neural Network Model Building**
   - Input layer configuration
   - Hidden layers with activation functions
   - Output layer for binary classification
   - Loss function and optimizer selection

4. **Task 4: Training and Evaluation**
   - Model training with validation
   - Performance metrics (accuracy, loss)
   - Confusion matrix
   - Classification report

5. **Task 5: Hyperparameter Experimentation**
   - Experiment 1: Baseline model
   - Experiment 2: Deeper network
   - Experiment 3: Different learning rate
   - Experiment 4: Adjusted batch size
   - Comparison table and analysis

6. **Task 6: Final Reflection**
   - Role of weights and biases
   - Importance of activation functions
   - Learning rate effects
   - Overfitting/underfitting analysis

## 📈 Results

The notebook includes:
- **Training/Validation curves** showing model learning progress
- **Confusion matrices** for performance visualization
- **Comparison tables** of different model configurations
- **Detailed analysis** of hyperparameter effects

## 🔍 Key Findings

Results and insights are documented in the notebook, including:
- Optimal hyperparameter configurations
- Model performance metrics
- Analysis of overfitting/underfitting
- Recommendations for model improvement

## 📚 Technologies Used

- **Python 3.x**: Programming language
- **TensorFlow/Keras**: Deep learning framework
- **Pandas**: Data manipulation
- **NumPy**: Numerical computing
- **Scikit-learn**: Preprocessing and metrics
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development environment

## 📝 Project Structure

```
part-1-neural-network-analysis/
├── notebook.ipynb          # Main Jupyter notebook with all tasks
├── README.md              # This file
├── requirements.txt       # Python dependencies
└── results/              # Directory for saved models and plots
```

## 🎓 Learning Outcomes

By completing this project, you will understand:
- How neural networks learn through forward and backward propagation
- The role of weights, biases, and activation functions
- Impact of hyperparameters on model performance
- How to identify and address overfitting/underfitting
- Best practices for neural network development

## 📧 Contact & Support

For questions or issues related to this project, please refer to the course materials or contact your instructor.

## 📄 License

This project is part of an educational assignment for Applied Neural Networks, Computer Vision, NLP & AI course.

---

**Note**: Make sure the dataset file `customer_churn_nn.csv` is available in the `../part_1_neural_network_analysis/` directory before running the notebook.