# Sisteme mobile si aplicatii
#### This project is a mobile application designed to detect Romanian SMS phishing (smishing) attempts, specifically tailored for seniors through an accessible "Grandma Friendly Mode" interface with human-readable threat explanations. 
#### The app features three main screens: a message scanner, a verdict screen with plain-language alerts, and a history log. 
#### For data management, it implements full local CRUD operations using a SQLite database to view, annotate and delete past scans. The system integrates two hardware components: the phone's camera (sensor) for OCR text extraction via Google ML Kit, and the vibration motor (actuator) to physically warn users upon detecting high-risk messages. 
#### Built natively in Android Studio using Kotlin, the app communicates via REST API with a mock Python FastAPI backend, which mimics the final XGBoost and SHAP explainability pipeline for development and evaluation purposes.
