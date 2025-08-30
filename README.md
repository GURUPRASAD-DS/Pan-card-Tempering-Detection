# Pan-card-Tempering-Detection
Computer Vision and Deep Learning
🪪 PAN Card Tampering Detection App

This project is a Flask/Gradio-based web application that detects whether a given PAN card image is Original or Tampered using the Structural Similarity Index Measure (SSIM).

The app allows users to upload a PAN card image, and it automatically compares it against the genuine reference PAN card to check for tampering.

🚀 Features

Upload a single PAN card image

Compute SSIM score between uploaded and reference PAN card

Decision rule:

SSIM < 31 → Tampered ❌

SSIM ≥ 31 → Original ✅

Interactive Gradio dashboard for easy use

Real-time detection with image preview

🛠️ Tech Stack

Python

OpenCV (image processing)

scikit-image (SSIM calculation)

Gradio (interactive web app)

📂 Project Structure
Pan-Card-Tampering-Detection/
│── original.jpg              # Reference PAN card image (genuine)
│── app.ipynb                 # Colab Notebook (Gradio app code)
│── README.md                 # Project documentation

⚙️ Installation & Setup

Clone the repository / upload notebook to Google Colab

Install dependencies:

pip install gradio scikit-image opencv-python


Place your original PAN card image in the working directory as original.jpg

Run the app in Colab:

demo.launch()

🎯 Usage

Open the Gradio link after running the notebook

Upload a PAN card image

The app displays:

SSIM Score

Detection Result (Original / Tampered)

Image Preview

🔍 Example Output

Input: Uploaded PAN card image

Output:

Original ✅ (SSIM Score: 85.6)

Tampered ❌ (SSIM Score: 22.4)

📌 Future Improvements

Highlight tampered regions using SSIM difference maps

Support for multiple image comparisons

Deployment on Flask/Streamlit + Cloud (Heroku/AWS/GCP)

👨‍💻Done By:

Guru Prasad
Aspiring Data Scientist | Machine Learning & Deep Learning Enthusiast 🚀

Do you want me to also prepare a shorter README version (4–5 sections only) for GitHub, or a detailed one with screenshots & usage examples?
