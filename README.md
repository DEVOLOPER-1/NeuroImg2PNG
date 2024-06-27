# 🧠 NeuroImg2PNG: Efficient Neuroimaging Conversion 🖼️

## Overview

Welcome to the NeuroImg2PNG repository! This project is designed to streamline the process of converting neuroimaging files, specifically `.nii` files, into PNG images. Leveraging Google Colab and Google Drive integration, this notebook provides an efficient way to handle large neuroimaging datasets without the hassle of excessive data transfer.

## ✨ Features

- **🌐 Google Drive Integration**: Directly access and save files on Google Drive, reducing the need for data upload/download.
- **🚀 Efficient Decompression**: Automatically uncompress `.nii.gz` files to `.nii` format within your Google Drive directory.
- **🌀 4D fMRI to PNG Conversion**: Converts 4D fMRI scans into PNG images, looping through time points.
- **📸 3D sMRI to PNG Conversion**: Converts 3D sMRI scans into PNG images.
- **📊 Optimized for Bandwidth**: Minimizes data usage and bandwidth by handling all operations within Google Drive and Google Colab.

## 🛠️ How It Works

### Step 1: Setup
First, the notebook installs the necessary libraries for neuroimaging data processing.

### Step 2: Library Imports
Key libraries such as `nibabel`, `numpy`, `matplotlib`, and `cv2` are imported to handle neuroimaging data and image processing.

### Step 3: Google Drive Mounting
Mount your Google Drive to access and store files directly from your cloud storage. This integration ensures that large files are managed efficiently.

### Step 4: Directory Setup
Specify the directories in your Google Drive where your `.gz` compressed files and output images will be stored.

### Step 5: Data Cleansing and Extraction
The notebook scans the specified directory for `.nii.gz` files, decompresses them to `.nii` format, and saves them in the same directory. This process ensures that you have uncompressed `.nii` files ready for conversion without additional data transfer.

### Step 6: Conversion to PNG
- **🌀 fMRI Conversion**: The notebook loops through the time points of 4D fMRI scans, converting each slice into a PNG image and saving them in the specified output directory.
- **📸 sMRI Conversion**: Similarly, 3D sMRI scans are converted to PNG images and saved.

## 🌟 Why This Approach?

By leveraging the power of Google Colab and Google Drive, this notebook provides a seamless and efficient workflow for handling large neuroimaging datasets. Users benefit from reduced data transfer times, optimized bandwidth usage, and the convenience of cloud-based storage and processing.

## 💡 Highly Recommended Environment

This notebook is highly recommended to be used on **Google Colab** due to its seamless integration with Google Drive and the computational resources it provides, making it ideal for handling large neuroimaging datasets.

## 🚀 Getting Started

1. **Clone the Repository**: Clone this repository to your local machine or directly open the notebook in Google Colab.
2. **Mount Google Drive**: Follow the instructions in the notebook to mount your Google Drive.
3. **Set Directories**: Specify the paths to your `.gz` files and the desired output directories.
4. **Run the Notebook**: Execute the cells to decompress, convert, and save your neuroimaging files as PNG images.

## 🎉 Conclusion

NeuroImg2PNG simplifies the conversion of neuroimaging files, making it accessible and efficient for researchers and practitioners. By integrating cloud-based tools, this project ensures that you can handle large datasets with ease and minimal resource usage.

---
## Stay in Touch 📬
Thank you for using NeuroImg2PNG! If you have any questions or need any more help, please feel free to reach out.

[https://www.linkedin.com/in/youssef-mohammad-9341a71a7?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3Bv9IaR6wuSWawwmi8p2Kjjg%3D%3D
](https://shorturl.at/nQqEd)
