## Movie Recommendation System Using Facial Recognition
Small description about the project like one below
The integration of a chatbot within a hostel booking system, aimed at streamlining the reservation process for students and improving the overall user experience.

## About
<!--Detailed Description about the project-->
In the modern digital entertainment era, users are exposed to an overwhelming number of movie choices across various platforms. Traditional movie recommendation systems rely primarily on user ratings, watch history, and genre preferences, which often fail to capture the user’s real-time emotional state. This project proposes an Emotion-Based Movie Recommendation System that uses facial recognition and real-time emotion detection to provide personalized movie suggestions.
The system captures live video input through a webcam and analyzes facial expressions using deep learning techniques to detect emotions such as happy, sad, angry, neutral, fear, and surprise. Based on the detected emotion, the system maps the emotion to suitable movie genres and fetches relevant movie recommendations from an online movie database. This approach eliminates the need for manual input and enhances user experience by offering instant, emotion-aware recommendations.
The proposed system integrates computer vision, machine learning, and real-time data processing to create an intelligent and interactive recommendation platform. It is efficient, user-friendly, and can be extended to OTT platforms, smart TVs, and personalized entertainment systems in the future

## Features
<!--List the features of the project as shown below-->
-Real-time emotion detection using facial recognition.

-Personalized movie recommendations based on detected emotion.

-Integration with TMDb API to fetch popular movies and posters.

-High accuracy in emotion detection leveraging DeepFace library.

-Interactive interface displaying movie posters in real-time.

-Easy-to-deploy Python application with minimal time complexity.

## Requirements
<!--List the requirements of the project as shown below-->
Operating System: 64-bit Windows 10 or Ubuntu.

Development Environment: Python 3.6 or later.

Deep Learning & Facial Recognition: DeepFace for emotion detection and OpenCV for real-time image processing and webcam interaction.

Movie Database Integration: TMDb API (requires API key) for fetching movies and posters.

Additional Libraries: requests for fetching images from URLs and numpy for image array processing.

IDE & Version Control: VSCode for coding and debugging and Git for version control and collaborative development.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

<img width="420" height="435" alt="Screenshot 2026-01-07 170543" src="https://github.com/user-attachments/assets/b911dc81-ebeb-4c88-b37d-46ac2671e8bf" />
<img width="640" height="328" alt="Screenshot 2026-01-07 170605" src="https://github.com/user-attachments/assets/175f9a67-bd1f-4462-9000-2c2f3aaeccf8" />

## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 -  emotion analysing

<img width="1441" height="281" alt="Screenshot 2026-01-07 171034" src="https://github.com/user-attachments/assets/dd2f73b2-2581-45c5-b701-301cb6c833d5" />

#### Output2 - Recommendations printed based on your emotion detected
<img width="1195" height="322" alt="Screenshot 2026-01-07 171341" src="https://github.com/user-attachments/assets/c0da3ee9-b79a-455c-b6fc-7535edcd8ce0" />

Detection Accuracy: 96.7%



## Results and Impact
<!--Give the results and impact as shown below-->
The Emotion-Based Movie Recommendation System successfully demonstrates the integration of DeepFace and deep learning techniques to bridge the gap between human affect and digital content. By moving beyond traditional "static" recommendations (based solely on watch history), this system introduces a dynamic, context-aware experience.
•	Accuracy: Using the DeepFace framework, the system achieved a high level of accuracy in identifying seven core emotions under varying lighting conditions.

•	User Engagement: Real-time feedback significantly reduces "decision fatigue" for users by automatically filtering thousands of movies into a mood-aligned shortlist.

•	Technical Efficiency: The modular architecture—separating data collection, preprocessing, and model inference—ensures that the system is lightweight enough to run on standard consumer hardware without significant lag.

•	Core Achievement: The project proves that facial expressions are a viable and powerful implicit feedback mechanism for personalized recommender systems.


This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References
[1] Qingna Pu, Bin Hu, "Intelligent movie recommendation system based on hybrid recommendation algorithms," in 2023 International Conference on Ambient Intelligence, Knowledge Informatics and Industrial Electronics, 2023.

[2] Angira Amit Patel, Dr. Jyotindra N. Dharwa, "An integrated hybrid recommendation model using graph database," in 2016 International Conference on ICT in Business Industry & Government (ICTBIG), 2016.

[3] F. Maxwell Harper, Joseph A. Konstan, "The MovieLens datasets: history and context," ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19, 2015.

[4] Prasanna Pramod Jain, Yash Dipak Patil, Yogeshwar Pawade, "Music and movie recommendation through emotion detection," in 2023 IJNRD, Volume 8, 2023. 

[5] Jaladi Sam Joel, B. Ernest Thompson, Steve Renny Thomas, T. Revanth Kumar, Shajin Prince, Bini D, "Emotion based music recommendation system using deep learning model," in 2023 International Conference on Inventive Computation Technologies (ICICT), 2023.

[6] Ms T Manju, Jayashakthi R, Nivethitha R, Lavanya P, "User- centric emotion modeling for next-generation recommender system," in 2023 International Conference on Research Methodologies in Knowledge Management, Artificial Intelligence and Telecommunication Engineering, 2023.

[7]  Serengil, S. I., & Ozpinar, A. (2020). LightFace: A Hybrid Deep Face Recognition Framework. 2020 Innovations in Intelligent Systems and Applications Conference (ASYU).




