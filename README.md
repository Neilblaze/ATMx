<p align="center">
  <img src="assets/Header.png">
</p>

## Description

- **Year**: 2023 <br/>
- **Organisation**: [TensorFlow](https://www.tensorflow.org) <img src="https://github.com/google/mediapipe/assets/48355572/5205ea50-174c-4bb3-b2e9-b4564ad1a9c7" width="14.5px" height="15.5px">
- **Project Title**: [Interactive Web Demos using the MediaPipe Machine Learning Library](https://summerofcode.withgoogle.com/programs/2023/projects/pd9KgnNP)
- **Mentor**: [Jen Person](https://www.linkedin.com/in/jennifer-person) ([@jenperson](https://github.com/jenperson))


<br/> 

## Project Details
An interactive web app which enables users to perform **contactless interactions** with the interface using simple human gestures. ✨

> **Background**: The *COVID-19 pandemic* <img src="https://github.com/google/mediapipe/assets/48355572/8c2b1254-5323-4742-b0ec-f4a7c2232dfd" width="14.5px" height="15.5px"> has increased awareness of hygiene risks associated with touchscreens, with reports indicating that **80%** of people find them *unhygienic*. **Touchless** *gesture-based* intuitive systems can reduce transmission in public settings and workplaces, and offer a seamless and convenient experience. Touchless technology is expected to remain popular in various industries, such as retail, healthcare, and hospitality. 

The web app highlights a special **ATM** which showcases an <ins>augmented transaction panel, enabling users to interact accurately through intuitive gestures detected from an input video feed</ins>. Users can perform essential operations directly through the interactive floating panel (on screen) via custom simple-to-use gestures, allowing them to experience the checkout process without the need for physical touch. <br/>



<details><summary><b>Shortened Version <img src="https://user-images.githubusercontent.com/48355572/234978665-08b7d16e-dace-479a-a061-478972c43f6b.gif" width="14px" height="14px"></b></summary><br/>In a rapidly evolving technological landscape, the aftermath of the COVID-19 pandemic has amplified concerns regarding hygiene and touch-based interactions. With **80%** of individuals deeming public touchscreens *unhygienic*, there is a compelling need for innovative solutions. Enter touchless gesture-based systems, poised to reshape industries and public spaces. Seamlessly aligning with the post-pandemic era, this technology offers intuitive and convenient interactions. From **ATMs** and airports to healthcare and retail, touchless interactions are on the brink of becoming ubiquitous. This project directly addresses these changing expectations by harnessing the power of the MediaPipe <a href="https://developers.google.com/mediapipe/api/solutions/js/tasks-vision.handlandmarker">Hand Landmarker</a>
 task from MediaPipe Solutions. By precisely detecting <a href="https://developers.google.com/mediapipe/solutions/vision/hand_landmarker#models">21</a>
 key hand landmarks, this technology powers an interactive web application enabling users to effortlessly engage with interfaces through contactless gestures. Designed for optimal performance in well-lit environments and on larger screens, this project embodies the future of safer, more advanced interactions.</details>



<br/>


## Project Report

Google’s [MediaPipe Solutions](https://developers.google.com/mediapipe/solutions/guide) helps developers add machine learning to their end-user devices, including mobile, web, and IoT. It provides a framework that lets you configure prebuilt processing pipelines that deliver immediate, engaging, and useful output to users.

The demo showcases the capabilities of the MediaPipe [Hand Landmarker](https://developers.google.com/mediapipe/api/solutions/js/tasks-vision.handlandmarker) task, which accurately detects and tracks [21](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker#models) hand landmarks. These landmarks are utilized in the **web app** to enable users to perform contactless interactions with the interface using simple gestures.

<br/>

![demoHeader](https://user-images.githubusercontent.com/48355572/263637727-4f15f4cf-3786-4914-8734-7dcf258f0429.png)

> ⓘ Best experienced in well-lit environments. Ideal on larger screens. All data taken via input video feed is deleted after returning inference and is computed directly on the client side, making it GDPR compliant.

<br/>

#### 🔸 Play with the Live Demo → [**Here**](https://atm-playground.netlify.app) ✨
#### 🔸 Alternate CodeSandbox <img src="https://user-images.githubusercontent.com/48355572/263678308-90ed1881-a6f6-4453-842e-67200c44f970.png" width="14.5px" height="14.5px"> Template → [**Here**](https://codesandbox.io/p/sandbox/quizzical-neco-svhglk) ✨
#### 🔸 View the Installation Notes → [**Here**](https://github.com/googlesamples/mediapipe/blob/main/tutorials/atm_playground/README.md#installation) ✨
#### 🔸 Explore the Official Repository → [**Here**](https://github.com/googlesamples/mediapipe/tree/main/tutorials/atm_playground) ✨


<br/>

💡 The source code for the demo includes detailed comments that explain the implementation and rationale behind the design decisions. 

<br/>

## Contributions <img src="https://user-images.githubusercontent.com/48355572/263670717-89cefc3e-346f-4b89-9f3a-36d7f14bb25c.png" width="18.5px" height="20px">
Throughout the summer, I have made multiple contributions to [MediaPipe](https://github.com/googlesamples/mediapipe). It's to be noted that chunks of git commits have been `rebased` into each of them, including:

- [x] [`app`]: MediaPipe Interactive Web Demo — Contactless ATM Playground, ([#209](https://github.com/googlesamples/mediapipe/pull/209))
- [x] [`feat`]: Adding Offline Support for Interactive Web Demo, ([#215](https://github.com/googlesamples/mediapipe/pull/215))
- [ ] [`style`]: Formatting & Asset Optimization, (WIP)

<br/>


## Blogs
Over the course of my GSoC journey, I've penned down blogs to share my insights, and here they are, presented in reverse chronological order:

| No. | Blog Title                                                  | Description                                                           | Link                                                                                     |
|-----|------------------------------------------------------------|-----------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| 1   | **Interactive Web Demo** <img src="https://user-images.githubusercontent.com/48355572/263672801-5929885f-9227-4be3-a686-ea3fbeff13d2.gif" width="12.5px" height="12.5px">                                       | Step-by-step guide to a touchless interactive web demo.               | [Link](https://blog.neilblaze.live/interactive-web-demo/)                              |
| 2   | Predicting Custom Gestures for Interactive Web Demo        | Exploring how to predict custom gestures for interactive demos.      | [Link](https://blog.neilblaze.live/predicting-custom-gestures-for-interactive-web-demo/) |
| 3   | A Holistic Preview of MediaPipe                            | A comprehensive look into MediaPipe's capabilities and potential.    | [Link](https://blog.neilblaze.live/a-holistic-preview-of-mediapipe/)                   |
| 4   | GSoC'23 Community Bonding Period                           | Insights into community bonding during GSoC 2023 preparations.      | [Link](https://blog.neilblaze.live/gsoc'23-community-bonding-period)                   |

<br/>

> ⓘ This documentation is intended to assist other developers in utilizing the MediaPipe library and implementing similar touchless interaction features in their projects.

<br/>



![dotted-bar-long](https://user-images.githubusercontent.com/48355572/263612162-32246a50-238b-48d7-aa6d-f1562b04ce3a.png)

## Architecture Overview 🔻

![AppArchitecture](https://user-images.githubusercontent.com/48355572/263662302-c6f096a8-01dd-4b38-ab61-04b85e8c91fb.png)

> **ⓘ** If you want to delve deep into the specs of the model, feel free to explore the official docs, which can be found [`here`](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker#models). You can access the official `model card` for MediaPipe Hands (Lite/Full) [here](https://drive.google.com/file/d/1-rmIgTfuCbBPW_IFHkh3f0-U_lnGrWpg/view). It provides detailed information about the model.

<br/>

## Interactive Web Demo 🔻

https://user-images.githubusercontent.com/48355572/260839719-c75b83f2-5978-4190-8197-6fb0f4b5dcfa.mp4

> ⚠️ Webcam is essential & required for hand detection and gesture recognition. Please ensure your device has a functioning webcam.

<br/>

![dotted-bar-long](https://user-images.githubusercontent.com/48355572/263612162-32246a50-238b-48d7-aa6d-f1562b04ce3a.png)



<br/>



## References

[1] MediaPipe Hands Official Paper: &nbsp; ([**LINK**🔗](https://arxiv.org/pdf/2006.10214.pdf))

[2] Applying Hand Gesture Recognition for User Guide Application Using MediaPipe (Paper): &nbsp; ([**LINK**🔗](https://www.researchgate.net/publication/357216549_Applying_Hand_Gesture_Recognition_for_User_Guide_Application_Using_MediaPipe))

[3] MediaPipe Solutions API Docs: &nbsp; ([**LINK**🔗](https://developers.google.com/mediapipe/api/solutions/js/tasks-vision.handlandmarker))


<br/>



## License 
Copyright 2023 The MediaPipe Authors. Distributed under the Apache License 2.0. See [`LICENSE`](https://github.com/Neilblaze/GSOC-23/blob/main/Interactive%20Demo/LICENSE) for more information.

<br/>



## Summary

Participating in **Google Summer of Code** (GSoC) for the first time was a fantastic experience. I'm deeply grateful to my mentor, [Jen Person 👩](https://github.com/jenperson), for this opportunity. Her invaluable feedback propelled the project. 

> Special Thanks to [**Paul Ruiz**](https://www.linkedin.com/in/paultruiz) ([@PaulTR](https://github.com/PaulTR)) for providing immense support and guidance throughout the program, & [**Jason Mayes**](https://www.linkedin.com/in/creativetech) ([@jasonmayes](https://github.com/jasonmayes)) for his valuable feedback on the proposal.

Beyond GSoC, I'm committed to ongoing contributions. Numerous exciting features remain to be explored. Count on me for consistent patches and updates to keep the project current. Feel free to connect on Twitter or LinkedIn for suggestions and feedback! 😄


<br/><br/>
<p align='center'>
<a href="https://atm-playground.netlify.app"><img height="23" src="https://user-images.githubusercontent.com/48355572/263659103-363b80e1-89f1-485b-b2d4-2d010458c1a5.png"></a>
</p>
