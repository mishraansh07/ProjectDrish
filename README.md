Drishti AI: AI-Powered Agronomist for Crop Disease Diagnosis

Empowering Farmers with Immediate, Data-Driven Agricultural Insights.

Table of Contents

Executive Summary

The Problem

Our Solution

Core Features

The Master Dataset

Technology Stack

Getting Started

Project Status

Future Roadmap

Team Lead

License

Executive Summary

Drishti AI is a deep learning system designed to provide immediate, expert-level crop disease diagnosis using smartphone imagery. By leveraging a custom-trained AI model developed through extensive data engineering on a curated dataset of over 170,000 images, Drishti AI aims to democratize agricultural expertise. We empower farmers, particularly in regions like Lucknow, Uttar Pradesh, with actionable insights to protect yields, reduce costs, and improve livelihoods.

The Problem

Smallholder farmers face significant economic risk from crop diseases. Timely and accurate identification is critical for effective treatment, yet access to qualified agronomists is often limited by cost and geography. Misdiagnosis leads to ineffective resource allocation (e.g., incorrect pesticides), financial losses, and potentially devastating harvest failures. Drishti AI directly addresses this critical information gap by providing accessible, reliable, and instantaneous diagnostic capabilities.

Our Solution

Our solution utilizes a sophisticated computer vision model integrated into a simple, user-friendly interface.

User Workflow:

Capture: A farmer captures or uploads an image of a symptomatic plant leaf.

Analyze: The image is processed by the Drishti AI model in the backend.

Diagnose: The system returns a diagnosis identifying the suspected disease, along with a confidence score indicating the model's certainty.

This provides immediate, data-driven diagnostic support, enabling informed decision-making regarding crop treatment and management.

Core Features

Instant AI-Powered Diagnosis: Identify plant diseases from a single image.

High-Confidence Predictions: Each diagnosis is accompanied by a confidence score.

Broad Crop & Disease Coverage: Trained on 41 unique classes covering a wide range of common crops and diseases.

Scalable Architecture: Built to support future enhancements like pest detection and treatment recommendations.

The Master Dataset

The power of Drishti AI comes from its high-quality, custom-built master dataset.

Total Images: ~174,000

Unique Classes: 41

Data Curation: The dataset was built by aggregating, intelligently merging, and cleaning data from 10+ public sources. All images have been standardized to a uniform 256x256 pixel resolution.

Splits: The final dataset is split for robust model training:

Training Set: 80%

Validation Set: 10%

Test Set: 10%

Technology Stack

Machine Learning: Python, TensorFlow, Keras

Data Processing: Pandas, NumPy, Pillow (PIL)

Development Environment: Kaggle Notebooks

Backend (Planned): Flask / FastAPI

Frontend (Planned): HTML/CSS, JavaScript

Getting Started

To get a local copy up and running, follow these simple steps.

Prerequisites:

Git LFS: You must have Git Large File Storage installed to handle the dataset file. You can install it from git-lfs.github.com.

git lfs install


Python 3.9+

Installation:

Clone the repository:

git clone [https://github.com/YOUR_USERNAME/Drishti-AI-Project.git](https://github.com/YOUR_USERNAME/Drishti-AI-Project.git)
cd Drishti-AI-Project


Set up a virtual environment (recommended):

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`


Install the required packages:

pip install -r requirements.txt


Project Status

The project is currently in the prototyping phase. The master dataset has been successfully built, and the focus is now on model training and building a web-based user interface.

Future Roadmap

[ ] Phase 1: Train and validate the baseline model on the master dataset.

[ ] Phase 2: Develop a Flask-based web application for user interaction.

[ ] Phase 3: Implement a treatment recommendation module.

[ ] Phase 4: Expand the dataset to include pest and nutrient deficiency diagnostics.

[ ] Phase 5: Deploy a full-fledged mobile application.

Team Lead

Ansh Mishra

License

This project is distributed under the MIT License. See LICENSE for more information.
