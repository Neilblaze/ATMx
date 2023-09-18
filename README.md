# ATMx 🏧 

An Interactive (Proof of Concept) Web Demo showcasing **Touchless Interactions** using the [MediaPipe](https://developers.google.com/mediapipe/) Machine Learning Library ✨


<p align="center">
<img src="https://user-images.githubusercontent.com/48355572/263637727-4f15f4cf-3786-4914-8734-7dcf258f0429.png" alt="cover-img">
</p>

Touchless gesture-based systems hold the potential to reshape public spaces, workplaces, and industries as it's seamless and convenient nature aligns with the post-pandemic landscape. This innovative webapp harnesses the power of the MediaPipe Handlandmarker Task, featuring an <ins>augmented transaction panel that enables users to interact effortlessly through intuitive hand gestures</ins>, detected from the input video feed. Notably, user data collected from the video feed is promptly deleted after inference, ensuring [GDPR](https://gdpr-info.eu) compliance as all computations occur client-side. Users can seamlessly perform essential operations via the on-screen interactive panel, utilizing straightforward custom gestures to navigate the checkout process without the need for physical touch, and it can even run offline! I was able to pioneer a novel method by leveraging custom logic to detect hand gestures directly via the HandLandmarker task, eliminating the reliance on heavyweight dependencies like the GestureRecognizer Task. This optimization not only streamlined the project but also contributed to enhancing the core MediaPipe framework's efficiency. The process involves segmenting the video stream to identify hands, localizing the palm area, and subsequently tracking specific hand keypoints for precise gesture recognition. This comprehensive approach significantly enhances performance, seamlessly integrating with the default Handlandmarker API. This project is a symbol of my commitment to embracing the future, harnessing innovation, and crafting a more hygienic, efficient, and enchanting way to connect with technology!

> This project aims to test and demonstrate the capabilities of the new MediaPipe [Hand Landmarker](https://developers.google.com/mediapipe/api/solutions/js/tasks-vision.handlandmarker) task from MediaPipe Solutions, which outputs 21 hand landmarks. The task provides precise and accurate hand landmark detection, generating [21](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker#models) key points on the hand. These landmarks are utilized in this interactive web app which enables users to perform contactless interactions with the interface using simple human gestures. Best experienced in well-lit environments. Ideal on larger screens.



<details><summary><b>Shortened Version <img src="https://user-images.githubusercontent.com/48355572/234978665-08b7d16e-dace-479a-a061-478972c43f6b.gif" width="14px" height="14px"></b></summary><br/>In a rapidly evolving technological landscape, the aftermath of the COVID-19 pandemic has amplified concerns regarding hygiene and touch-based interactions. With <b>80%</b> of individuals deeming public touchscreens <em>unhygienic</em>, there is a compelling need for innovative solutions. Enter touchless gesture-based systems, poised to reshape industries and public spaces. Seamlessly aligning with the post-pandemic era, this technology offers intuitive and convenient interactions. From <b>ATMs</b> and airports to healthcare and retail, touchless interactions are on the brink of becoming ubiquitous. This project directly addresses these changing expectations by harnessing the power of the MediaPipe <a href="https://developers.google.com/mediapipe/api/solutions/js/tasks-vision.handlandmarker">Hand Landmarker</a> task from MediaPipe Solutions. By precisely detecting <a href="https://developers.google.com/mediapipe/solutions/vision/hand_landmarker#models">21</a> key hand landmarks, this technology powers an interactive web application enabling users to effortlessly engage with interfaces through contactless gestures. Designed for optimal performance in well-lit environments and on larger screens, this project embodies the future of safer, more advanced interactions.</details>

<br/>
<br/>

<p align="center">
<img src="https://user-images.githubusercontent.com/48355572/260842692-34bcee72-228a-4b24-84be-146c4973bd18.gif" alt="demo-gif">
</p>


<p align='center'>
<a href="https://github.com/Neilblaze/ATMx/actions/workflows/testing.yml"><img height="20" src="https://github.com/Neilblaze/ATMx/actions/workflows/testing.yml/badge.svg"></a> &nbsp; <a href="https://github.com/Neilblaze/ATMx/actions/workflows/node.js.yml"><img height="20" src="https://github.com/Neilblaze/ATMx/actions/workflows/node.js.yml/badge.svg"></a> &nbsp; <a href="https://github.com/Neilblaze/ATMx/actions/workflows/testing.yml"><img height="20" src="https://user-images.githubusercontent.com/48355572/268592369-40eba7e1-38ab-4665-a80a-f0315c7f6b89.svg"></a> &nbsp; <a href="https://atmx.neilblaze.live"><img height="20" src="https://user-images.githubusercontent.com/48355572/263659103-363b80e1-89f1-485b-b2d4-2d010458c1a5.png"></a>
</p>

<br/>


## Prerequisites
This project requires [Node.js](https://nodejs.org/en/download) to be installed on your local machine.

> ⚠️ Webcam required for hand detection and gesture recognition. Please ensure your device has a functioning webcam.


<br/>


## Installation

1. Clone the repository on your local machine:
    ```sh
    git clone https://github.com/Neilblaze/ATMx.git
    ```

2. Navigate into the project directory:
    ```sh
    cd ATMx
    ```

3. Install the necessary dependencies:
    ```sh
    npm install
    ```

4. Start the development server:
    ```sh
    npm start
    ```

5. Open the project in your browser at [`http://localhost:3000`](http://localhost:3000) to view your project.


<br/>


> 🚀 View a _live demo_ in your browser [**here.**](https://atmx.neilblaze.live) 


<br/>


## Built With
This project was created using:
<img align="right" style="padding-top: 20px;" src="https://user-images.githubusercontent.com/48355572/268604224-c22e8fb5-43f0-4009-b2f3-a5336085d977.png" alt="QR-Code" width="337" />

- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [MediaPipe Hand Landmarker](https://developers.google.com/mediapipe/api/solutions/js/tasks-vision.handlandmarker)
- [Redux](https://redux.js.org/)
- [React Redux](https://react-redux.js.org/)
- [PostCSS](https://postcss.org/)
- [React Toastify](https://github.com/fkhadra/react-toastify/)
- [React Confetti](https://github.com/alampros/react-confetti/)
- [Figma](https://www.figma.com/)


<br/>

### Case Study
This project is part of my [contribution](https://github.com/Neilblaze/GSOC-23) as a mentee in Google Summer of Code 2023, working under the TensorFlow org, & is a symbol of my commitment to embracing the future, harnessing innovation, and crafting a more hygienic, efficient, and enchanting way to connect with technology! 

I wrote a comprehensive article on this project, which you can read [**here**](https://blog.neilblaze.live/interactive-web-demo). <img src="https://user-images.githubusercontent.com/48355572/263672801-5929885f-9227-4be3-a686-ea3fbeff13d2.gif" width="12.5px" height="12.5px">

> ⓘ This is intended to assist other developers in utilizing the MediaPipe library and implementing similar touchless interaction features in their projects.

## Architecture Overview 🔻

![AppArchitecture](https://user-images.githubusercontent.com/48355572/263662302-c6f096a8-01dd-4b38-ab61-04b85e8c91fb.png)

> **ⓘ** If you want to delve deep into the specs of the model, feel free to explore the official docs, which can be found [`here`](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker#models). You can access the official `model card` for MediaPipe Hands (Lite/Full) [here](https://drive.google.com/file/d/1-rmIgTfuCbBPW_IFHkh3f0-U_lnGrWpg/view). It provides detailed information about the model.

<br/>



## References

[1] MediaPipe Hands Official Paper: &nbsp; ([**LINK**🔗](https://arxiv.org/pdf/2006.10214.pdf))

[2] Applying Hand Gesture Recognition for User Guide Application Using MediaPipe (Paper): &nbsp; ([**LINK**🔗](https://www.researchgate.net/publication/357216549_Applying_Hand_Gesture_Recognition_for_User_Guide_Application_Using_MediaPipe))

[3] MediaPipe Solutions API Docs: &nbsp; ([**LINK**🔗](https://developers.google.com/mediapipe/api/solutions/js/tasks-vision.handlandmarker))



<br/>

![dotted-bar-long](https://user-images.githubusercontent.com/48355572/263612162-32246a50-238b-48d7-aa6d-f1562b04ce3a.png)

### Update (v0.1.1)
Precaching is enabled! Hence, the app will work offline after the first load. 🎉

## Contact
Pratyay Banerjee — [dev@neilblaze.live](mailto:pratyaybanerjeex@gmail.com)

## License
Distributed under the Apache License 2.0. See [`LICENSE`](./LICENSE) for more information.
