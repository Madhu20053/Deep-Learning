# 🌟 Ultimate Photo Restoration

A powerful desktop application for restoring old and damaged photos using advanced computer vision techniques. Features intelligent crack removal, face enhancement, and professional-grade image restoration.

**License:** MIT  
**Technologies:** Python, OpenCV, NumPy, Pillow, scikit-image, SciPy, Tkinter  

Inspired by: [Bringing Old Photos Back to Life (CVPR 2020)](https://openaccess.thecvf.com/content_CVPR_2020/html/Wan_Bringing_Old_Photos_Back_to_Life_CVPR_2020_paper.html)  
This project implements a lightweight, user-friendly version using classical computer vision techniques instead of deep learning.

---

## ✨ Features

### 🎯 Core Capabilities
- **Ultimate Face Clarity** – Advanced face detection and enhancement with eye detail optimization  
- **Superior Crack Removal** – Multi-scale intelligent inpainting that preserves important features  
- **Feature Preservation** – Smart algorithms that protect facial features during restoration  
- **Professional Quality** – Multi-stage enhancement pipeline for maximum quality  

### 🛠️ Restoration Methods

#### 👤 Face-Focused Restoration
- **Ultimate Face Clarity** – Maximum face enhancement with detail preservation  
- **Smart Face Enhancement** – Balanced face improvement  
- **Eye & Detail Enhancement** – Specialized eye and facial feature enhancement  

#### 🔧 Crack & Damage Removal
- **Intelligent Inpainting** – Advanced crack detection and removal  
- **Multi-Scale Crack Fix** – Processes cracks at multiple resolutions  
- **Feature-Preserving Fix** – Removes damage while protecting important details  

#### 🏆 Complete Restoration
- **ULTIMATE RESTORATION** – Full pipeline combining all techniques (5-8 minutes)  
- **Portrait Perfection** – Optimized for portrait photos  
- **Professional Grade** – Studio-quality restoration  

---

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/ultimate-photo-restoration.git
cd ultimate-photo-restoration
pip install -r requirements.txt
Usage
🖥️ GUI Application (Recommended)

Windows:

ULTIMATE_RESTORATION.bat


Mac/Linux:

python ultimate_photo_restoration.py

💻 Command Line Interface

Basic usage:

python ultimate_cli.py your_photo.jpg


With specific modes:

# Face enhancement only (2-3 minutes)
python ultimate_cli.py portrait.jpg face

# Crack removal only (3-4 minutes)
python ultimate_cli.py damaged.jpg crack

# Complete restoration (5-8 minutes)
python ultimate_cli.py old_photo.jpg ultimate


Sample test:

python ultimate_cli.py test_images/old_w_scratch/a.png ultimate

📸 How It Works
The Ultimate Restoration Pipeline

This project uses classical computer vision techniques (no deep learning required):

1. Multi-Scale Crack Detection

Analyzes image at multiple resolutions (1.0x, 0.8x, 0.6x, 0.4x)

Morphological operations (tophat, blackhat)

Edge detection (Canny, Sobel, Laplacian)

Adaptive thresholding for crack identification

Combines multiple detection methods with weighted blending

2. Intelligent Inpainting

Telea (Fast Marching Method) – Better for textured areas

Navier-Stokes – Better for smooth areas

Large radius Telea – Preserves structures

Blends results intelligently based on local variance and edge strength

Protects facial features from aggressive inpainting

3. Face Detection & Enhancement

Detects faces using OpenCV Haar Cascades

Advanced CLAHE (Contrast Limited Adaptive Histogram Equalization)

Multi-scale processing (0.5x, 1.0x, 1.5x, 2.0x) for optimal detail

Specialized eye enhancement with targeted sharpening

Unsharp masking at multiple frequencies

Bilateral filtering for skin smoothing

4. Final Quality Optimization

Advanced noise reduction (Non-local Means Denoising)

Selective sharpening based on edges

Color enhancement in LAB color space

Bilateral filtering for smooth results

Adaptive processing based on local characteristics

Advantages

✅ No GPU required
✅ Fast processing (2-8 minutes)
✅ Works offline
✅ Easy to understand and modify

Trade-offs vs Deep Learning

⚠️ Less sophisticated than state-of-the-art deep learning models
⚠️ May not handle extreme degradation as well
✅ But much more accessible and practical for everyday use

🎨 GUI Features

Visual Before/After Comparison

Multiple Processing Options (9 restoration methods)

Customizable Settings:

Enhancement level (Conservative, Balanced, Maximum)

Focus areas (Faces, Eyes, Texture)

Processing options (Noise reduction, Color enhancement)

Sample Images – Built-in test images

High-Quality Export

📋 Requirements

Python 3.6+

OpenCV (cv2)

NumPy

Pillow (PIL)

scikit-image

SciPy

tkinter (usually included with Python)

🖼️ Sample Results

Best with:

Old family photos with cracks and scratches

Faded portraits

Damaged historical photographs

Low-quality scanned images

⚙️ Advanced Options

Enhancement Levels:

Conservative – Subtle improvements

Balanced – Good balance

Maximum Quality – Aggressive enhancement

Processing Time:

Face enhancement: 2-3 minutes

Crack removal: 3-4 minutes

Ultimate restoration: 5-8 minutes

🤝 Contributing

Contributions are welcome! You can:

Report bugs

Suggest new features

Submit pull requests

Improve documentation

📝 License

This project is licensed under the MIT License. See the LICENSE file for details.

🙏 Acknowledgments

Inspired by the following research:

"Bringing Old Photos Back to Life" (CVPR 2020, Oral)

"Old Photo Restoration via Deep Latent Space Translation" (TPAMI 2022)

Authors: Ziyu Wan, Bo Zhang, Dongdong Chen, Pan Zhang, Dong Chen, Jing Liao, Fang Wen

Citation:

@inproceedings{wan2020bringing,
  title={Bringing Old Photos Back to Life},
  author={Wan, Ziyu and Zhang, Bo and Chen, Dongdong and Zhang, Pan and Chen, Dong and Liao, Jing and Wen, Fang},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={2747--2757},
  year={2020}
}

@article{wan2020old,
  title={Old Photo Restoration via Deep Latent Space Translation},
  author={Wan, Ziyu and Zhang, Bo and Chen, Dongdong and Zhang, Pan and Chen, Dong and Liao, Jing and Wen, Fang},
  journal={arXiv preprint arXiv:2009.07047},
  year={2020}
}

💡 Tips for Best Results

Portraits: Use "Ultimate Face Clarity" or "Portrait Perfection"

Damaged photos: Use "ULTIMATE RESTORATION"

Quick fixes: Use "Smart Face Enhancement" or "Intelligent Inpainting"

Recommended image size: 500x500 to 2000x2000 pixels

🐛 Troubleshooting

GUI won't start:
Ensure tkinter is installed:

python -m tkinter


Run from command line to see error messages.

Out of memory errors:
Resize large images, close other applications, or use CLI mode.

Poor results:
Experiment with different enhancement levels and restoration methods.
Some images may need manual touch-up.

📧 Contact

For questions, issues, or suggestions, please open an issue on GitHub.

Made with ❤️ for preserving precious memories.


---

If you want, I can also **add a Table of Contents and badges** at the top to make it look more professional on GitHub. It will make it very clean and navigable.  

Do you want me to do that?
