# **Neural Style Transfer**  

## **Implemented Paper**  
**Title:** *Image Style Transfer Using Convolutional Neural Networks*  
**Authors:** Leon A. Gatys, Alexander S. Ecker, Matthias Bethge  
**Paper Link:** [CVPR 2016](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)  

---

## **Input**  

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Content Image</b> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Style Image</b>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e5d9d68c-b844-4122-b769-013996e27856" align="left" alt="Content Image" width="350" height="350">
  <img src="https://github.com/user-attachments/assets/2c696cd7-9707-4f47-9f6d-fa7a2416c179" alt="Style Image" width="300" height="350">
</p>


---

## **Output**  

### **Using Adam Optimizer**  
![Adam Optimizer Output](https://github.com/user-attachments/assets/c9dded16-9f31-44b9-b10b-4508a86f2737)  

### **Using L-BFGS Optimizer**  
![L-BFGS Optimizer Output](https://github.com/user-attachments/assets/5b3e1ddd-446e-4eee-91ca-da34528d7c15)  

---

## **Description**  
This project implements the **Neural Style Transfer** technique described in the paper *Image Style Transfer Using Convolutional Neural Networks*. The model takes a **content image** and a **style image** and synthesizes an output image that retains the structure of the content while incorporating the style patterns.  

Different **optimizers** are used:  
- **Adam Optimizer:** Fast convergence but may get stuck in local minima.  
- **L-BFGS Optimizer:** Generally produces sharper and better-quality results.  

---
