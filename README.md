# Noisy Image Recovery Using Spatial Filtering

## Digital Image Processing Mini Project

This project demonstrates image restoration using spatial filtering techniques.

Gaussian noise and salt-and-pepper noise are introduced into an input image.
Mean and median filters are then applied to recover the degraded image.
The results are evaluated using MSE, PSNR, and SSIM.

## Objectives

- Study the effect of noise on digital images.
- Add Gaussian and salt-and-pepper noise to an input image.
- Apply mean and median spatial filters.
- Compare the restored results.
- Evaluate image quality using MSE, PSNR, and SSIM.

## Technologies Used

- Python
- Google Colab
- OpenCV
- NumPy
- Matplotlib
- scikit-image

## Methodology

Input Image
→ Grayscale Conversion
→ Noise Addition
→ Spatial Filtering
→ Result Comparison
→ MSE / PSNR / SSIM Evaluation

## Techniques Used

### Noise Models
- Gaussian Noise
- Salt-and-Pepper Noise

### Restoration Techniques
- Mean Filter
- Median Filter

### Evaluation Metrics
- Mean Squared Error (MSE)
- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index (SSIM)

## Project Structure

```text
Noisy-Image-Recovery-DIP/
├── README.md
├── Noisy_Image_Recovery_Colab.ipynb
├── images/
├── screenshots/
├── report/
│   └── Noisy_Image_Recovery_DIP_Project_Report.docx
└── requirements.txt
```

## How to Run

1. Open `Noisy_Image_Recovery_Colab.ipynb` in Google Colab.
2. Run the cells from top to bottom.
3. Upload an image when the notebook asks for it.
4. Review the generated noisy and restored images.
5. Record the MSE, PSNR, and SSIM results.
6. Add the final output images to the `images/` folder.
7. Add important Colab output screenshots to the `screenshots/` folder.

## Results

The notebook generates:
- Original grayscale image
- Gaussian noisy image
- Salt-and-pepper noisy image
- Mean-filtered results
- Median-filtered results
- MSE, PSNR, and SSIM values

The final numerical results depend on the input image and the noise generated during execution.

## Limitations

- The project uses a small image set.
- Only Gaussian and salt-and-pepper noise are considered.
- Filter performance depends on parameter selection.
- Strong filtering can remove useful image details.

## Future Scope

- Use a larger and more diverse image dataset.
- Test additional noise types such as speckle noise.
- Explore adaptive and frequency-domain filtering.
- Test real noisy photographs.
- Explore deep learning-based image restoration.
- Develop a real-time or web-based restoration system.

## Report

The `report/` folder contains the project report following the required mini-project report structure.

## GitHub Submission

The complete project should be hosted in a separate GitHub repository as required by the Digital Image Processing mini-project guidelines.
