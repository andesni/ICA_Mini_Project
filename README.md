# ICA Mini Project

This project demonstrates the use of Independent Component Analysis (ICA) for Blind Source Separation on image data. It focuses on separating mixed images into their original sources using ICA and visualizing the results.

## Objective
- **Goal**: To use ICA to separate mixed images back into their original sources.
- **Method**: The project generates mixed images using a random mixing matrix, then applies ICA to separate them back to the original images.
- **Tools**: Python, Jupyter Notebook, NumPy, Matplotlib, scikit-learn.

## Files Included
1. **ICA_Mini_Project.ipynb**: Jupyter Notebook with the code for ICA implementation and visualization of results.
2. **Images**: Mixed and separated images used and generated by the ICA algorithm.
3. **README.md**: Information about the project.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ICA_Mini_Project.git

## Results
Mixed Images: The mixed images are a combination of multiple source images created by applying a random mixing matrix. These images are not recognizable as individual sources.
Separated Images: After applying ICA, the algorithm successfully separates the mixed images back into their original components. The separated images should resemble the original sources, although some distortion may occur depending on the mixing process and the number of components used.
Visualizations: The notebook contains visualizations of both the mixed images and the separated images, allowing you to compare the effectiveness of ICA in recovering the original sources.
![image](https://github.com/user-attachments/assets/821bedc1-fa0f-419c-9cb0-af1f267c7e83)
Images were randomly selected from Google
