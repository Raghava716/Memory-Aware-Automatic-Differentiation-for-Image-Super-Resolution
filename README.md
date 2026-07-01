# Memory-Aware Automatic Differentiation for Optimization-Based Image Super-Resolution

<p align="center">
  <img src="images/workflow.png" width="800">
</p>

## 📌 Overview
This project presents a memory-efficient image super-resolution framework that combines deep learning and optimization techniques to reconstruct high-resolution images from low-resolution inputs.

The proposed approach utilizes:
- **FSRCNN (Fast Super-Resolution Convolutional Neural Network)** for efficient image reconstruction.
- **Automatic Differentiation (AD)** for gradient-based image refinement.
- **Conjugate Gradient (CG)** optimization to improve convergence and enhance image quality.

The objective is to generate high-quality images while minimizing computational and memory requirements, making the solution suitable for resource-constrained environments.

---

## 🚀 Features
- Lightweight and memory-efficient super-resolution framework.
- Deep learning-based image reconstruction using FSRCNN.
- Gradient optimization using Automatic Differentiation.
- Image refinement using Conjugate Gradient optimization.
- Performance evaluation using PSNR and SSIM metrics.
- Suitable for medical imaging, surveillance, satellite imaging, and mobile photography applications.

---

## 🛠️ Tech Stack

- Python
- PyTorch
- NumPy
- OpenCV
- Matplotlib
- Scikit-Image
- Jupyter Notebook

---

## 📂 Project Structure

text
Memory-Aware-Image-Super-Resolution/
│
├── dataset/
├── notebooks/
├── models/
│   └── fsrcnn_model.py
├── optimization/
│   ├── automatic_differentiation.py
│   └── conjugate_gradient.py
├── outputs/
├── images/
├── requirements.txt
└── README.md


---

## 🔬 Methodology

### Step 1: Data Preprocessing
- Load high-resolution images.
- Generate low-resolution images using bicubic downsampling.
- Resize and normalize images.

### Step 2: Model Training
- Train the FSRCNN model on paired LR-HR images.

### Step 3: Automatic Differentiation
- Compute gradients efficiently.
- Minimize reconstruction loss.

### Step 4: Conjugate Gradient Optimization
- Refine the generated image.
- Improve convergence and preserve image details.

### Final Pipeline

```text
Low Resolution Image
        ↓
      FSRCNN
        ↓
Automatic Differentiation
        ↓
Conjugate Gradient
        ↓
High Resolution Output
```

---

## 📊 Evaluation Metrics

### Peak Signal-to-Noise Ratio (PSNR)
Measures reconstruction quality.

### Structural Similarity Index (SSIM)
Measures structural similarity between the original and reconstructed images.

---

## 📈 Results

The proposed framework achieves:
- Improved PSNR and SSIM scores.
- Better edge preservation.
- Reduced noise.
- Lower memory consumption compared to traditional methods.

---

## 🖼️ Sample Outputs

| Input | FSRCNN | FSRCNN + AD | FSRCNN + AD + CG |
|-------|---------|-------------|------------------|
| Low Resolution | Enhanced | Refined | Final Output |

---

## 🔮 Future Work

- Real-time image super-resolution.
- Deployment on mobile and edge devices.
- Integration with transformer-based architectures.
- Video super-resolution extension.

---

## 📚 Applications

- Medical Imaging
- Surveillance Systems
- Satellite Imaging
- Mobile Photography
- Remote Sensing

---

## 👨‍💻 Author

**Venkat Raghava C G**  
M.Sc. Data Science  
Vellore Institute of Technology, Chennai

📧 Email: your-email@example.com  
🔗 LinkedIn: https://www.linkedin.com/in/your-linkedin-profile  
💻 GitHub: https://github.com/your-github-username

---

## ⭐ If you found this project useful, please consider giving it a star!
