# SkillsterAI 

This is a submission for the Samsung Prism GenAI hackathon 2024 by Sahnaaz Mariam (2nd Year ECM) and Lakshmanan (2nd Year ECE) of Vellore Institute of Technology, Chennai. 

SkillsterAI, with its tagline 'making hobbies accessible' is a platform where anyone can easily adopt a hobby, progress from beginner to expert levels with guidance from our AI expert, and receive valuable feedback. Our mission is to democratize skill acquisition, making it both cost-free and readily available to all.
 
In our initial development phase, SkillsterAI concentrates on sports, dance, yoga, and gymnastics. We accomplish this by training a machine learning model with datasets containing movements performed by athletes and practitioners. These movements are then compared with the user's performance in the aforementioned hobbies using MediaPose pose detection technology, analyzing poses frame by frame. By providing detailed feedback based on this comparison, SkillsterAI empowers users to enhance their skills and proficiency levels in their chosen activities. 


# Mediapose Pose Detection

1. **Input**: The pose detection algorithm typically receives an image or a video frame as input.

2. **Preprocessing**: The input image undergoes preprocessing to ensure compatibility with the pose detection model. This may involve resizing, normalization, or other transformations.

3. **Model Inference**: After preprocessing, the pre-trained pose detection model processes the image, identifying key points corresponding to different body parts. These key points represent the pose of the person in the image.

4. **Post-processing**: Following key point detection, post-processing techniques may be applied to refine the detected poses. This can include smoothing, interpolation, or filtering to enhance the accuracy and stability of the detected poses.

5. **Output**: The output of the pose detection algorithm typically consists of the coordinates of key points corresponding to various body parts. Additionally, it may provide additional information such as confidence scores or pose landmarks.

6. **Visualization**: Optionally, the detected poses can be visualized by overlaying them onto the original image or video frame. This visualization aids in understanding the detected poses and assessing their accuracy.

   
<img width="275" alt="Screenshot 2024-03-23 at 7 36 48 PM" src="https://github.com/Sahnaaz/SkillsterAI/assets/152959675/81eb8070-49cd-4d1d-a48a-708c94bf6f6e">

# Setting up capsule in Bixby

1. Create a New Capsule: Within the Bixby Developer Studio, a new capsule should be created. This capsule serves as the project where the developer defines Bixby actions and models.

2. Define Concepts and Actions: Concepts, which are data models, and actions that the capsule will support must be defined. This entails specifying the information the capsule will handle and the actions users can perform.

3. Implement JavaScript Logic: JavaScript code should be written to handle the actions defined within the capsule. This code executes when users interact with the capsule through Bixby.

4. Test the Capsule: The simulator within the Bixby Developer Studio is utilized to test the capsule's functionality. The developer ensures that it behaves as expected and gracefully handles various user inputs.

5. Refine and Iterate: Based on testing feedback, the capsule is refined. This may involve adjustments to models, enhancements to the user experience, or debugging of the code.

6. Publish the Capsule: Once the capsule is deemed ready, it can be published to the Bixby Marketplace, allowing others to utilize it.
   
