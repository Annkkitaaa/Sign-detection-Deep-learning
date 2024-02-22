# Sign-detection-Deep-learning

1. Data Collection:
Utilize OpenCV to capture images, collecting a minimum of 5 images for each sign involved in the conversion process outlined in this thesis.

2. Image Labeling:
Establish the Label IMG framework for efficient image labeling.
Label collected images to facilitate subsequent image detection via Single Shot Multibox Detector (SSD).

3. Data Preprocessing:
Employ an appropriate sampling method to divide the collected dataset into training and testing datasets.

4. Model Training:
Apply transfer learning techniques to train the deep learning model.

5. Update Checkpoints:
Implement checkpoints to save the current state of the pre-trained model during the training process.


6. Real-Time Detection:
Develop an interactive web interface using Streamlit to enable real-time detection of sign language and its conversion to text.
