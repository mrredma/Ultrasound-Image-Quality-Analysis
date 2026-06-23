# 🩺 Ultrasound Image Quality Analyzer

A powerful **web-based tool** for automatic **no-reference quality assessment** of medical ultrasound images.

Built with **Streamlit**, OpenCV, and scikit-image — perfect for radiologists, sonographers, researchers, and medical imaging professionals.

![Demo](https://via.placeholder.com/800x400?text=Ultrasound+Quality+Analyzer+Demo)  
*(Add a screenshot here after deployment)*

## ✨ Features

- **Sharpness Analysis** (Laplacian Variance)
- **Contrast Measurement** (RMS Contrast)
- **Signal-to-Noise Ratio (SNR)**
- **Contrast-to-Noise Ratio (CNR)**
- **Entropy** (Information Content)
- **Edge Detection & Noise Visualization**
- **Histogram Analysis**
- **Overall Quality Score** with recommendations
- **Download Detailed Report** (CSV)

## 🚀 Live Demo

[Open the App](https://your-app-name.streamlit.app)  
*(Update this link after deploying on Streamlit Cloud)*

## 📸 How to Use

1. Visit the web app
2. Upload any ultrasound image (PNG, JPG, TIFF, BMP)
3. Get instant quality metrics and visual analysis
4. Download the detailed report

## 🛠️ Technologies Used

- **Streamlit** – Web Interface
- **OpenCV** – Image Processing
- **scikit-image** – Advanced Metrics
- **Pillow** – Image Handling
- **Matplotlib** – Visualization

## 📊 Quality Metrics Explained

| Metric                        | What it measures                  | Good Value       |
|------------------------------|-----------------------------------|------------------|
| Sharpness (Laplacian)        | Image clarity / focus             | > 400            |
| RMS Contrast                 | Overall contrast level            | > 35             |
| Estimated SNR                | Signal vs Noise                   | > 14 dB          |
| CNR                          | Tissue differentiation            | Higher is better |
| Entropy                      | Information richness              | Higher is better |

## 🏥 Use Cases

- Quality control in ultrasound departments
- Research in medical image processing
- Training sonographers
- Pre-processing validation before AI analysis
- Equipment performance monitoring

## 📥 Installation (Local)

```bash
git clone https://github.com/YOURUSERNAME/ultrasound-quality-analyzer.git
cd ultrasound-quality-analyzer
pip install -r requirements.txt
streamlit run app.py