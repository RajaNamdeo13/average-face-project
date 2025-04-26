
Average Face Generator
This project creates an average face by blending multiple face images based on facial landmark points.
It uses OpenCV, NumPy, and affine transformations to align faces and generate a smooth, averaged output.

📋 Project Overview
Input:

5–6 face images (e.g., of presidents) in .jpg format.

Corresponding .txt files containing 68 facial landmark points for each image.

Process:

Read images and their landmark points.

Align faces using similarity transformations (based on eye corners).

Warp each face to a common frame.

Average all faces pixel-by-pixel to generate a final blended face.

Output:

One image showing the average face created from all input images.

🛠️ Technologies Used
Python 3

OpenCV

NumPy

(Optional) Google Colab for running the code online.

📂 Folder Structure
bash
Copy
Edit
average-face-project/
├── code.py         # Main Python script
├── images/         # Folder containing input .jpg and .txt files
├── README.md       # Project documentation
└── LICENSE         # License file
🚀 How to Run
Place all .jpg and .txt files inside the images/ folder.

Make sure the path variable inside code.py points to the correct folder.

Run the script:

bash
Copy
Edit
python code.py
The result (average face) will be displayed after processing.

📌 Important Notes
Each .txt file must have exactly 68 (x, y) points (one per line).

Images and landmark files should correspond correctly (same name or correct order).

Output face size is 600 × 600 pixels (can be changed in the code).

📜 License
This project is licensed under the MIT License.

🎯 Example Output
(Optional: You can add an output image here to showcase your result.)

🤝 Acknowledgements
Special thanks to:

OpenCV community

Public face datasets

Tutorials and guides on facial landmark alignment****
