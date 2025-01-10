Enhanced Multi-View Medical Image Viewer

A comprehensive PyQt6 application for visualizing medical imaging data. This software supports DICOM and NIFTI file formats, providing synchronized axial, sagittal, coronal, and 3D views, making it ideal for medical researchers and practitioners.

Features

-Multi-View Display:

-Axial, sagittal, and coronal views.

-Interactive crosshairs for synchronized navigation.

-3D Visualization:

-GPU-based volume rendering.

-Adjustable opacity and color transfer functions for better anatomical insights.

-Image Manipulation:

-Brightness and contrast adjustment.

-Zoom and pan functionality.

File Format Support:

-Load DICOM series from a folder.

-Load NIFTI files (.nii and .nii.gz).

Cine Playback:

Play, pause, and stop navigation through slices.

User-Friendly UI:

Intuitive sliders for slice navigation.

Toolbar for quick actions.

Side panel for advanced settings.

Installation

Prerequisites

Ensure you have the following installed:

Python 3.9 or higher

pip package manager

Steps

Clone the repository

Install the required dependencies:

pip install -r requirements.txt

Run the application:

python MPR.py

Usage:

Launch the application.

Use the "Load File" button or toolbar option to load medical imaging data.

Navigate through slices using the provided sliders or mouse interactions.

Adjust brightness and contrast using the side panel controls.

Switch between pointer and hand modes for precise interactions.

Explore synchronized views and detailed 3D visualization.

Requirements

Python Libraries:

PyQt6

VTK

NumPy

Pydicom

Nibabel

Install all dependencies using:

pip install PyQt6 vtk numpy pydicom nibabel

Screenshots:

## Screenshots

### Application View
![Load file](Screenshot/Capture.png)

![Application View](Screenshot/1.png)

![Application View](Screenshot/2.png)


License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements

Special thanks to open-source libraries like PyQt6, VTK, and NumPy for enabling this project.