# TY-Sem-6-Mini_project
Face Detection 

#### Project Description:
This project utilizes deep learning models to classify whether an input image contains a real or fake face. It also provides explainability by highlighting areas of the image that contribute most to the model's prediction.

#### Technologies Used:
- Python
- PyTorch
- Gradio
- facenet_pytorch
- pytorch-grad-cam
- NumPy
- OpenCV

#### Directory Structure:
```
- /images
  - /real_images
  - /fake_images
- model.py
- predict.py
- requirements.txt
- README.md
```

#### Code Files:
1. `model.py`: Contains the model architecture and training script.
2. `predict.py`: Implements the prediction function using the trained model.
3. `requirements.txt`: Lists all dependencies for easy environment setup.

#### Instructions to Run:
1. Clone the repository: `git clone https://github.com/your_username/real-vs-fake-face-detection.git`
2. Navigate to the project directory: `cd real-vs-fake-face-detection`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the prediction interface: `python predict.py`
5. Upload an image and see the classification result along with the explainability visualization.

#### Documentation:
- **Usage**: Upload an image to the interface and see if it contains a real or fake face.
- **Output**: The interface displays the classification label (real or fake) along with an explainability visualization highlighting the regions contributing to the model's prediction.
- **Saving**: Flagged images are saved in separate directories (`/real_images` and `/fake_images`) based on the prediction.
- **Confidence Scores**: Confidence scores for both real and fake predictions are displayed.
#### Interface :
Input Image:
![image](https://github.com/Fazal-Ansari/TY-Sem-6-Mini_project/assets/106878663/9ecf7ba8-2df4-4883-9cb6-51d52164b786)
Result:
![image](https://github.com/Fazal-Ansari/TY-Sem-6-Mini_project/assets/106878663/8eb4d8e0-fb8b-40dc-ad81-7cebfffb0ffe)



