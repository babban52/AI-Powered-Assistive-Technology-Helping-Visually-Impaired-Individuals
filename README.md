# AI-Powered Assistive Technology: Helping Visually Impaired Individuals

![Project Image](https://github.com/babban52/AI-Powered-Assistive-Technology-Helping-Visually-Impaired-Individuals/blob/main/8ab45b16-eaef-4e12-b680-eeff2883bb15.jpeg)

## Project Overview

Drishti is an AI-powered assistive technology designed to help visually impaired individuals by providing real-time object detection and scene description. The system captures images from the surroundings, identifies objects using computer vision techniques, and conveys the information through audio cues, thereby enhancing situational awareness and navigation capabilities.

## Project Goal

The primary goal of Drishti is to empower visually impaired individuals by leveraging advanced image processing and machine learning techniques to offer real-time object recognition and scene understanding.

## Target Audience

Drishti is designed for individuals with visual impairments, helping them better perceive and interact with their environment, thereby promoting greater independence and accessibility.

## Project Workflow

1. **Image Acquisition**: Capturing visual data using a camera (webcam or smartphone camera).
2. **Object Detection**: Utilizing deep learning algorithms (e.g., YOLO, SSD) to detect objects within the captured images.
3. **Scene Description**: Generating text-based descriptions based on the identified objects and their spatial relationships.
4. **Audio Output**: Converting text descriptions into speech using a text-to-speech API.

## Technical Details

### Programming Language

- Python

### Libraries & Frameworks

- **OpenCV**: For image processing and manipulation.
- **TensorFlow/Keras**: For deep learning-based object detection.
- **Pyttsx3**: For converting text descriptions into audio speech.

### Hardware Requirements

- Camera (Webcam or Smartphone Camera)

## Key Features

- **Real-time Object Recognition**: Identifies and communicates objects in the environment.
- **Scene Understanding**: Generates meaningful captions to provide situational awareness.
- **Audio Feedback**: Converts text-based descriptions into speech for accessibility.
- **Improved Independence**: Enables visually impaired individuals to interact more freely with their surroundings.

## Challenges & Solutions

- **Computational Resources**: Real-time processing requires significant computational power. Cloud-based resources can be used to improve efficiency.
- **Environmental Factors**: Variations in lighting and occlusions can affect accuracy. Pre-processing techniques and robust machine learning models help mitigate this.
- **User Experience**: A user-friendly interface is crucial. Conducting usability studies and gathering feedback ensures better accessibility and usability.

## Future Enhancements

- **GPS & Navigation Integration**: Providing navigation assistance for complex environments.
- **Expanding Object Database**: Continuously training the model with new objects to enhance detection accuracy.
- **Customization & Accessibility**: Offering personalized settings to cater to different user needs and preferences.

## How to Use

1. Install the required dependencies using:
   ```bash
   pip install opencv-python tensorflow keras pyttsx3
   ```
2. Connect a camera device and run the program.
3. The system will capture images, detect objects, and provide real-time audio feedback.

## Contact

For further details or contributions, please reach out to debraj.mahato.official@gmail.com.

---

Drishti aims to be a step forward in making the world more accessible for visually impaired individuals through the power of AI and assistive technology.

