# Epicardial Fat Segmentation
Code for automatic segmentation of epicardial fat starting from a DICOM set of images.
Main code has been taken taken from HARTA repo: https://github.com/aforebelo/HARTA.
Output is a .nii.gz image with segmented fat superimposed to CCTA.
## HARTA software
HARTA is software developed in the context of a master thesis project.
- Rebelo, A. F. O. (2021). Semi-automatic approach for epicardial fat segmentation and quantification on non-contrast cardiac CT. Dissertation submitted in partial fulfillment of the requirements for the degree of Master of Science in Biomedical Engineering, NOVA University of Lisbon, NOVA Scholl of Science and Technology.

This application comes as an answer to the time-consuming task of manually segmenting epicardial fat on CT images. The proposed algorithm uses exclusively basic image operations, so no training steps are required. This software must be seen as a prototype that can be upgraded and optimized with the community's suggestions.

Feel free to contact me! Here is my email: afo.rebelo@campus.fct.unl.pt.

![All text](https://github.com/aforebelo/HARTA/blob/main/Screenshots/5_Semiautomatic_result.png)

## Getting Started
To use HARTA, follow the next steps:
1. Install Python 3.8.3
2. Access to the environment variables of Windows
3. Open the directory of Python
4. Copy the Python folder path (e.g., C:\Python38\) and the folder Scripts path (e.g., C:\Python38\Scripts\)
5. Download and extract the zip file of this repository
6. Open the terminal in the folder
7. Run the following lines

```pip install -r requirements.txt```

```python3 harta.py```

8. Enjoy HARTA!
