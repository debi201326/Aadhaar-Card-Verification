**Aadhaar Fraud Detection Project**

This project detects potential Aadhaar card fraud using deep learning, Optical Character Recognition (OCR), and face verification. It verifies data consistency in Aadhaar card details, compares faces in the card with user-uploaded images, and flags any anomalies in card information.

**Features:**
- Data Augmentation for Robust Model Training: Includes rotation, flipping, and scaling transformations to strengthen the model.
- Convolutional Neural Network (CNN) for classification: Trained to identify if an Aadhaar card is real or fake.
- OCR using Tesseract and EasyOCR: Extracts text details like name, DOB, gender, and Aadhaar number from uploaded Aadhaar card images.
- Face Verification with Face Recognition library: Compares the face on the Aadhaar card with a user-uploaded face photo.
- Anomaly Detection: Identifies missing or incorrect fields on the Aadhaar card, such as name, DOB, gender, or Aadhaar number format.

**Prerequisites**
Python 3.6+
Google Colab or similar Jupyter environment
Packages:
tensorflow
opencv-python-headless
easyocr
face_recognition

**Dataset Structure**
Organize the dataset as follows:
/content/drive/MyDrive/adhaar/
├── real/       # Folder containing real Aadhaar card images
└── fake/       # Folder containing fake Aadhaar card images

