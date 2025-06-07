# Mnist_Dataset_Quantization


🧠 MNIST Quantization with Keras
This project demonstrates how to apply Deep Learning Model Optimization techniques such as Pruning and Quantization using the MNIST dataset. It is built using TensorFlow/Keras and showcases different levels of model compression with accuracy benchmarking.

📁 Project Structure
       Quantization.ipynb: Main Jupyter notebook containing:

1. Model training on MNIST

2. Quantization-aware training (QAT)

3. Post-training quantization (PQT)

4. Model performance comparison

🚀 Techniques Covered
       ✅ Baseline model training
       
       ✅ Post-training quantization (int8)
       
       ✅ Quantization-aware training (QAT)
       
       ✅ Size and latency comparisons
       
       ✅ Accuracy and loss evaluation

📊 Sample Results (Model Comparison Table)


| Model              | Accuracy | Size    |
|--------------------|----------|---------|
| Baseline (float32) | 84.2%    | 1.17 MB  |
| QAT (Quantization Aware Training) | 84.1%    | 107 KB  |
| PQT (Post Training Quantization) | 86.9%    | 107 KB  |

**🛠 Requirements**
       pip install tensorflow numpy matplotlib

**🧪 How to Run**
      ** Clone the repository**

       **[Open Quantization.ipynb in Jupyter or Colab](url)**

**Run all cells step-by-step**

**📦 Future Plans**
       Add support for model export (.tflite)

Deploy compressed models to edge devices

**🤝 Credits**
      
         
       Dataset: MNIST
       
       Model optimization: TensorFlow Model Optimization Toolkit
