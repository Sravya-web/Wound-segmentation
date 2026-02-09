 Wound Segmentation using U-Net and Attention U-Net

 Overview
This project focuses on automatic wound area segmentation from images using deep learning.  
Accurate wound segmentation is important in healthcare for wound assessment, monitoring healing progress, and clinical documentation.

I implemented and compared U-Net and Attention U-Net architectures for pixel-wise segmentation of wound regions.

---

 Objectives
- To segment wound regions from foot images
- To compare U-Net and Attention U-Net performance
- To visualize predicted masks using overlays
- To evaluate model performance using Dice Coefficient

---

 Models Used
- **U-Net** – baseline segmentation model  
- **Attention U-Net – improves focus on wound regions by learning important spatial features  

---

 Dataset
- Images: Right top view of foot with wound  
- Annotation: Binary masks (wound vs background)  
- Annotation Tool: Label Studio  

---

 Workflow
1. Data collection  
2. Image annotation (Label Studio)  
3. Preprocessing (resize, normalization)  
4. Train U-Net & Attention U-Net  
5. Evaluate using Dice Coefficient  
6. Visualize predictions using mask overlays  

---

 Evaluation Metric
**Dice Coefficient**  
Used to measure overlap between predicted mask and ground truth.

---

 Results
| Original Image | Ground Truth Mask | Predicted Mask (Overlay) |

---

 Tech Stack
- Python  
- Google Colab  
- TensorFlow / PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  
- Label Studio

---

 Key Learnings
- Medical image annotation & preprocessing  
- Deep learning segmentation pipeline  
- U-Net vs Attention U-Net comparison  
- Evaluation using Dice Coefficient  
- Visualization of predictions. 

