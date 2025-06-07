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

📊 Sample Results (Example)
Model	Accuracy	Size
Baseline (float32)	98.2%	1.2 MB
QAT	98.1%	300 KB
PQT	97.9%	250 KB

🛠 Requirements
bash
Copy
Edit
pip install tensorflow numpy matplotlib
🧪 How to Run
Clone the repository

Open Quantization.ipynb in Jupyter or Colab

Run all cells step-by-step

📦 Future Plans
Add support for model export (.tflite)

Deploy compressed models to edge devices

Compare different datasets (Fashion MNIST, CIFAR-10)

🤝 Credits
Developed by: [Your Name]

Dataset: MNIST

Model optimization: TensorFlow Model Optimization Toolkit
