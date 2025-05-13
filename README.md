# 🔍 Image Forgery Detection using Structural Similarity and Contour Analysis

This project focuses on detecting image forgery or tampering by analyzing the structural similarity and shape-based features of two input images. It leverages **Structural Similarity Index (SSIM)** and **contour detection** techniques on grayscale binary representations of images to identify discrepancies.

## 🧠 How It Works

1. **Structural Similarity Index (SSIM):**
   Measures the similarity between the original and suspected image. A lower SSIM score (e.g., \~31.2%) indicates a high likelihood that the image is fake or tampered.

2. **Grayscale Thresholding and Contour Detection:**
   Converts both images to grayscale, applies thresholding, and extracts contours. This allows shape-based analysis and further highlights differences between the images.

3. **Visual Analysis:**
   The results are visualized by displaying:

   * Thresholded images
   * Contour outlines
   * Difference maps

These visual tools help in understanding and verifying any structural modifications or inconsistencies between the images.

## 🛠️ Use Cases

This project is particularly useful for organizations or institutions that require identity verification based on submitted image documents. Potential use cases include:

* Verifying identity cards (e.g., NID, Voter ID)
* Authenticating scanned documents or certificates
* Detecting tampered photographs in legal or administrative workflows

## 📌 Scope

Organizations such as banks, government agencies, or onboarding platforms can integrate this system to enhance their document verification pipeline. It adds an automated layer of fraud detection before manual review, saving time and increasing trust.

