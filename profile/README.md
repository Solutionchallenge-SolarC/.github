<br>

<p align="center">
<img src="https://github.com/user-attachments/assets/834d2ff8-d92b-4953-bc7d-82360bf1353b"  width="140px" alt="HearSitter Logo" />
</p>

<h1 align="center">SolarC</h1>

<br>

<br>
SolarC is an AI-driven solution designed to enhance healthcare accessibility for underserved rural communities and elderly individuals. It provides comprehensive skin health management, empowering users with accessible diagnostics, proactive sun protection, and seamless telemedicine.

## 📱 Screens
| Home Screen | Home Screen | Home Screen |
|:------------:|:-----------:|:-----------:|
| <img src="https://github.com/user-attachments/assets/672b1a38-20bf-4eb9-9e35-c403110506db" width="200" /> | <img src="https://github.com/user-attachments/assets/3c3cffd8-b5a5-4516-9e15-210a3f9e7962" width="200" /> | <img src="https://github.com/user-attachments/assets/891683d3-9175-4567-8c6a-d3e20d915782" width="200" /> |



## 🌻 Purpose
- Promote Early Intervention: Detect skin issues early with AI-powered analysis.
- Enable Comprehensive Skin Wellness: Track skin health over time and manage UV exposure.
- Improve Healthcare Accessibility: Offer telemedicine and hospital recommendations for remote users.

  
## 🔑 Key Features
### 📷 AI-Powered Skin Condition Identification
- EfficientNetB0 model analyzes skin images for condition detection.
### :dependabot: Interactive Chatbot with Questionnaire
- Personalized guidance based on user responses.
### 🔈 Voice Guidance
- Text-to-speech and speech-to-text for elderly users.
### 🏥 Hospital Search & Telemedicine Integration
- Seamlessly connects users with nearby hospitals and healthcare professionals via Jitsi Meet.
### 😎 UV Exposure Management
- Provides real-time UV index data and personalized warnings for sun protection.

## 📊 Model Training Data

For training the AI-powered skin condition analysis model, we use the **HAM10000** dataset, which consists of three key files:

1. **HAM10000_images_part_1** and **HAM10000_images_part_2**:  
   These files contain a large collection of skin lesion images. The images represent various dermatological conditions and are used to train the model for skin condition identification.

2. **HAM10000_metadata**:  
   This file contains metadata corresponding to the images in the above parts. The metadata includes the following information:
   - **Skin Condition**: Labels for different types of skin conditions (e.g., melanoma, basal cell carcinoma, etc.).
   - **Age**: The age of the individual who provided the skin image.
   - **Gender**: The gender of the individual.
   - **Location**: The geographical location where the image was taken or where the individual resides.

Due to the size of the dataset, these files are not hosted on GitHub. However, you can access the dataset by visiting [HAM10000 dataset repository](https://www.kaggle.com/datasets/). Please ensure proper usage and citation when working with the dataset.

This data is used to train the **EfficientNetB0** model to detect skin conditions accurately and offer personalized insights for users.


## 📱 How to run our app service
- [SolarC apk download link](https://drive.google.com/drive/folders/1pzuCWMWWPgkRfc13wPaOTt-7bwnggEbE?usp=sharing)
- Install the apk file on your android smartphone.

