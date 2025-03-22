# **MLP Dropout Analysis: Impact on Model Performance**  

##  Overview  
This project explores the effect of different dropout rates on the performance of a **Multi-Layer Perceptron (MLP)**. We analyze accuracy, loss trends, and overfitting behavior using **Python, TensorFlow/Keras, and Matplotlib**.  

##  Project Structure  
```
├── data/                 # (If any dataset is used)
├── models/               # Saved models (if applicable)
├── notebooks/            # Jupyter Notebooks for analysis
├── results/              # Accuracy, loss plots, and evaluation metrics
├── main.py               # Main script for training and evaluation
├── README.md             # Project documentation
└── requirements.txt      # Dependencies
```

##  Technologies Used
- Python  
- TensorFlow/Keras   
- Matplotlib   

##  Experiment Details 
- **Model:** Multi-Layer Perceptron (MLP)  
- **Hyperparameters:** Learning rate, batch size, dropout rates (0.1 to 0.5)  
- **Evaluation Metrics:** Accuracy, loss curves  

##  Key Findings
- Higher dropout rates reduce overfitting but may impact convergence speed.  
- Moderate dropout (~0.3) provides a balance between regularization and performance.  
- Training accuracy is higher with lower dropout, but test accuracy benefits from regularization.  

##  How to Run 
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/MLP-Dropout-Analysis.git  
   cd MLP-Dropout-Analysis  
   ```
2. Install dependencies:  
   ```sh
   pip install -r requirements.txt  
   ```
3. Run the main script:  
   ```sh
   python main.py  
   ```

##  Future Work 
- Test on different architectures (CNN, RNN, etc.)  
- Implement adaptive dropout strategies  
- Use a larger dataset for better generalization  
