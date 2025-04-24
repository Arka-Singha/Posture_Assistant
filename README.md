# Posture_Assistant

## Problem Statement

Health Concern: Poor posture leads to severe health issues such as Thoracic Kyphosis, Chronic Lower Back Pain, Cervical Spondylosis, Herniated Disc. Specially for those who use PC or laptop for long hours. Costly Solutions: Existing systems are expensive and bulky. Real-Time Need: This project aims to design a cost- effective, lightweight posture guidance system using computer vision and machine learning.

## Objectives
• Develop a portable device capable of analyzing seated posture in real time.
• Ensure affordability and scalability for diverse users.
• Integrate real-time feedback mechanisms to guide for a better posture.

## Societal Impact
• Health Benefits: Prevents posture-related health issues, enhancing overall well-being. 
• Economic Impact: Provides an affordable solution, accessible to a wide demographic. 
• Future Potential: Can be adapted for various environments like offices, schools, and homes.

## Methodology

1.Technology Used:
Machine learning algorithms for posture detection,. Computer vision frameworks (e.g., OpenCV, Media Pipe). Lightweight hardware compatible with low-power devices. 
2. Implementation:
Collected and annotated a dataset of seated postures. Trained a model to detect key body landmarks and classify posture
Designed a real-time feedback mechanism. 
3. Flowchart:
Input → Pose Detection → Posture Classification → Feedback
Output

<p align="center">
  <img src="https://github.com/user-attachments/assets/1010f358-f0e5-4c47-ba10-0781c7949147" width="500" alt="System Flow Diagram"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9e1f1510-3702-488d-a30b-226efa0df5a5" width="500" alt="System Flow Diagram"/>
</p>

![image](https://github.com/user-attachments/assets/1010f358-f0e5-4c47-ba10-0781c7949147)
![image](https://github.com/user-attachments/assets/9e1f1510-3702-488d-a30b-226efa0df5a5)


## 🔬 Experimental Results

Experiments Conducted :
• used pre-trained models for posture estimation. 
• trained models for seated-specific posture scenarios. 
• Demonstrated system compatibility with low-power devices like normal webcam.

### 💡 Note on  Exploration

In the latter stages of the project, we also explored:
- **CNN-based feature extraction** from posture keypoints.
      Achieved 62.78 % accuracy
- **MLP (Multi-Layer Perceptron)** models for binary classification.
      Achieved 91.79 % accuracy for upper body and 88.61 % accuracy for lower body due to feature extraction.
- Comparisons between rule-based logic and learned classifiers.

These insights could inform a more intelligent posture coach in future versions.


## ⚙️ Technologies Used

- **OpenCV** – Real-time image processing
- **MediaPipe BlazePose** – 3D Pose Estimation
- **YOLOv5** – Person detection
- **Python** – Core language
- **TensorFlow/Keras** – CNN and MLP models
- **Rule-based logic** – Angle-based formulas


## 📱 Future Enhancements

- 📲 **Mobile App** for feedback and tracking
- 📊 **Posture Analytics** dashboard with trends
- 🧑‍🤝‍🧑 Expand dataset to reflect cultural and ergonomic diversity
- 🧢 Integration with **wearable sensors** for hybrid feedback



## 🙌 Team Members

- Arka Singha  
- Anamitra Bhattacharyya  
- Abir Sarkar  
- Ananya Singh  


🎓 *Electronics & Computer Science Engineering*  
👨‍🏫 Guided by: Asst. Prof. Manoj Kumar Parida  
🏫 Kalinga Institute of Industrial Technology


## 📚 References

- [OpenPose by Cao et al., 2017](https://openaccess.thecvf.com/content_cvpr_2017/html/Cao_Realtime_Multi-Person_2D_CVPR_2017_paper.html) – Foundation of human pose estimation.
- [MediaPipe BlazePose](https://google.github.io/mediapipe/solutions/pose.html) – Used for keypoint detection.
- [Upright Pose Coach](https://www.uprightpose.com/) – Commercial comparison.


> 📌 *This is a mini-project with strong societal impact, aiming to democratize posture correction technology using accessible and scalable solutions.*

