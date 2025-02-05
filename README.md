# AI-Powered Violence Detection in CCTV Surveillance  

## 📌 Project Overview  
This project focuses on detecting violent activities in CCTV surveillance footage using deep learning techniques. By leveraging computer vision and machine learning, it aims to enhance public safety by providing real-time alerts for suspicious or violent behavior.  

## 🔍 Features  
- *Automated Violence Detection*: Identifies violent actions from CCTV footage.  
- *Deep Learning-Based Model*: Utilizes CNNs and RNNs for accurate classification.  
- *SmartCity CCTV Violence Detection Dataset*: Trained using the SCVD dataset.  
- *Real-Time Processing*: Capable of real-time inference for quick alerts.  
- *Scalability*: Can be integrated into existing security systems.  

## 🛠 Tech Stack  
- *Programming Language*: Python  
- *Frameworks & Libraries*: TensorFlow/PyTorch, OpenCV, NumPy, Pandas  
- *Dataset*: SmartCity CCTV Violence Detection Dataset (SCVD)  
- *Deployment*: Flask/FastAPI for API integration  

## 📂 Dataset  
The SmartCity CCTV Violence Detection Dataset (SCVD) from Kaggle serves as the primary dataset, containing labeled video clips for violent and non-violent actions.  

## ⚙ Installation & Setup  
1. Clone the repository:  
   bash
   git clone https://github.com/yourusername/violence-detection.git
   cd violence-detection
   
2. Install dependencies:  
   bash
   pip install -r requirements.txt
   
3. Download and preprocess the dataset.  
4. Train the model:  
   bash
   python train.py
   
5. Run inference on sample videos:  
   bash
   python detect.py --video sample.mp4
   

## 📈 Model Performance  
- *Accuracy*: [Add your accuracy score]  
- *Precision & Recall*: [Add metrics after evaluation]  

## 🚀 Future Enhancements  
- Improve accuracy with advanced architectures (e.g., Transformers).  
- Optimize real-time processing using lightweight models.  
- Implement multi-camera tracking and event correlation.  

