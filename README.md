# PurvaLaksana

An AI-powered healthcare companion empowering rural clinics and medical interns with advanced medical image analysis, heart monitoring, and risk assessment through a dual-interface system that supports clinical decision-making when senior doctors are unavailable.

## Project Overview

PurvaLaksana is a comprehensive healthcare solution integrating AI for medical image analysis, designed specifically to support healthcare delivery in resource-constrained settings. Our multi-user platform serves both patients and healthcare professionals, providing secure, accessible healthcare analysis at their fingertips.

**Vision:** Making advanced medical diagnostics accessible to everyone, especially in areas with limited specialist access.

## Live Demo and ppt and presentation video links

For Video Demo
[https://drive.google.com/drive/u/3/home](https://drive.google.com/file/d/1Oe_IghfVzKBcsAsn4oUIKT7QeNrnXotM/view?usp=share_link)

For ppt 
https://docs.google.com/presentation/d/1rUj-osOSw9LMpuM4ypk2f_lFPd-FrmKU/edit?usp=sharing&ouid=100389320335860981800&rtpof=true&sd=true


Experience PurvaLaksana in action:
- **Live Application:** [https://purvalaksana.streamlit.app](https://purvalaksana.streamlit.app)
- **Status:** Active and Running
- **Access:** Available 24/7 for testing and demonstration

### Demo Credentials
For testing purposes, you can use:
- **Patient Login:** Create a new account or use the registration feature
- **Test Doctor Login:** Click the "Login as Test Doctor" button on the login page
  - This provides immediate access to the doctor dashboard with sample patient data
  - Perfect for exploring the doctor-side features without registration

### Note
The live demo is hosted on Streamlit Cloud and represents the latest stable version of the application.

## Key Features

- **Medical Image Analysis:** Specialized detection models for various medical conditions
- **Heart Health Tools:** Risk assessment, report analysis, and real-time monitoring
- **Dual Interface System:**
  - Patient Portal: Self-service health analysis and personalized insights
  - Doctor Dashboard: Comprehensive patient management and analysis review
- **AI Chat Assistant:** Medical query support with natural language processing
- **PDF Report Generation:** Professional medical reports with analysis results
- **Hospital Locator:** Maps integration for finding nearby healthcare facilities
- **Video Backgrounds:** Immersive medical-themed video backgrounds for better UX
- **Language Translation:** Support for multiple languages using deep translation
- **Voice Assistance:** Text-to-speech and speech-to-text capabilities
- **Google Fit Integration:** Real-time health data synchronization
- **Dark Mode Support:** Enhanced visibility and reduced eye strain

## Use Cases

### For Rural Clinics
- Preliminary screening of medical images when specialists aren't available
- AI-assisted interpretation of lab reports and medical data
- Patient education through the AI assistant

### For Medical Interns
- Decision support when senior doctors are unavailable
- Training tool for recognizing medical conditions in images
- Validation of preliminary diagnoses

### For Patients
- Self-monitoring of health parameters
- Understanding medical reports in simplified language
- Access to preliminary screenings without long waiting periods

## Technology Stack

- **Frontend:** Streamlit for intuitive, responsive UI
- **AI/ML:** YOLO for image detection, Google Gemini for natural language processing
- **Database:** Supabase for secure data storage and retrieval
- **Authentication:** Custom user management system with role-based access
- **Integrations:** Google Fit API, geolocation services
- **Report Generation:** ReportLab for PDF generation

## Medical Analysis Capabilities

- **Brain Tumor Detection:** MRI scan analysis
- **Diabetic Retinopathy:** Eye image analysis
- **Heart Disease Prediction:** Cardiac health assessment with ML model
- **Bone Fracture Detection:** X-ray image analysis
- **Skin Disease Analysis:** Dermatological condition detection
- **Lung Cancer Detection:** Chest X-ray analysis
- **Ulcer Detection:** Oral cavity examination
- **Tongue Analysis:** Traditional medicine diagnostic support
- **Nail Disease Detection:** Nail health assessment
- **Blood Report Analysis:** Automated report interpretation
- **Heart Report Analysis:** ECG and cardiac report interpretation

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Git
- Google API keys for Generative AI
- Supabase account for database functionality

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/MadhavDGS/PurvaLaksana.git
   cd PurvaLaksana
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your environment variables:
   - Create a `.env` file in the project root directory
   - Add your API keys and credentials:
     ```
     GOOGLE_API_KEY=your_google_api_key
     SUPABASE_URL=your_supabase_url
     SUPABASE_KEY=your_supabase_key
     ```

### Running the Application

1. Start the Streamlit application:
   ```
   streamlit run login.py
   ```

2. Access the application in your browser:
   - The application will be available at http://localhost:8501
   - Use the provided login credentials or register a new account

3. Using the system:
   - For patients: Access the home page for medical image analysis
   - For doctors: Use the doctor dashboard to view patient records and analyses
  <img width="1470" alt="Screenshot 2025-04-12 at 9 57 47 PM" src="https://github.com/user-attachments/assets/f98d8a58-8f07-4228-bb15-506df93f8a25" />
<img width="1470" alt="Screenshot 2025-04-12 at 9 04 06 PM" src="https://github.com/user-attachments/assets/8aac5634-e3fa-452a-bc46-e792e4826543" />
## Testing

### Sample Test Images
The repository includes a `TestImages` directory with sample medical images for testing various analysis features:

- Brain MRI scans for tumor detection
- Eye images for diabetic retinopathy analysis
- Skin condition images
- Lung X-rays
- Blood report samples
- And more...

You can use these images to test the system's analysis capabilities without needing to upload your own medical images initially. These images are provided for demonstration purposes only.

### How to Use Test Images
1. Navigate to the appropriate analysis section in the application
2. Instead of uploading your own image, use one from the `TestImages` directory
3. Test different analysis features with relevant sample images
4. Review the AI's analysis and generated reports

Note: These test images are carefully selected examples and are meant for demonstration purposes only. Real medical analysis should be performed with actual patient images.


   

## Future Roadmap

- Additional disease detection models
- Mobile application development
- Integration with electronic health records
- Enhanced analytics and reporting
- Expanded language support

## Contributing

We welcome contributions to improve PurvaLaksana and make healthcare more accessible worldwide!

## Disclaimer

This tool provides preliminary analysis only and is not intended to replace professional medical advice, diagnosis, or treatment. Always consult qualified healthcare professionals for medical decisions.
