# Plant_disease_detection_using_CNN
This project implements a real-time plant disease detection system using Convolutional Neural Networks (CNNs) for accurate and efficient classification. The Streamlit-based frontend provides an interactive and user-friendly interface to upload plant images and receive instant disease predictions.

## Prerequisites  

- **Python 3.x** installed  
- **TensorFlow/Keras** for deep learning  
- **Streamlit** for the web-based frontend  
- **pip** (Python package manager)  
- **Virtual environment** (recommended)

### Dataset link: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

## Installation Steps  

## 1️⃣ Clone the Repository:  
    git clone https://github.com/lokeshveluru39/plant_disease_detection_using_CNN.git  
    cd plant_disease_detection_using_CNN

## 2️⃣ Create and Activate Virtual Environment:
    python -m venv venv 
## On Windows:
    venv\Scripts\activate  
## On macOS/Linux:
    source venv/bin/activate  
## 3️⃣ Install Dependencies:
    pip install -r requirements.txt  
## 4️⃣ Configure Environment Variables:
Create a .env file in the project root and add necessary configurations, such as model paths, API keys (if any), and database credentials.

## 5️⃣ Run the Application
## Backend (Model Inference API):
    python app.py  

## Frontend (Streamlit UI):
- streamlit run app.py  
-The application will be accessible at http://localhost:8501/.

### Running the Project

## Navigate to the Project Directory:
    cd plant-disease-detection  

## Run the Application:
    streamlit run app.py  
## Access the Web UI:
- Visit http://localhost:8501/ and upload an image to detect plant diseases.

### Common Issues and Solutions
1️⃣ Module Not Found Errors
✔ Ensure dependencies are installed with:
pip install -r requirements.txt  
✔ Activate the virtual environment before running commands.

2️⃣ Model Not Loading Properly
✔ Check if the pre-trained model file is available in the correct directory.
✔ Verify that the correct model path is set in the .env file.

3️⃣ Streamlit Not Found
✔ Install it manually with:
pip install streamlit  

4️⃣ App Not Running on Port 8501
✔ Change the port by running:
streamlit run app.py --server.port 8502 
 
Features<br>
✅ Deep Learning Model: Uses a trained CNN for plant disease classification.<br>
✅ Real-Time Detection: Quick inference for instant results.<br>
✅ Streamlit UI: Simple and interactive frontend.<br>
✅ Image Upload: Users can upload images for analysis.<br>
✅ Result Interpretation: Displays confidence scores and disease names.<br>
<br>
Tech Stack<br>
Backend: TensorFlow/Keras, OpenCV, NumPy<br>
Frontend: Streamlit<br>
Deployment: Local/Cloud<br>
