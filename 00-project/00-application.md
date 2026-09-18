---
name: Yusuf Atakan AKYUZ
neptun: OKG649
id: 2026-ST-04
---
# Camera-Based Monitoring, Automatic Tracking, and Route-Behaviour Analysis of Ant Colony Individuals

## My interpretation of the brief
My interpretation of the research project is that building a camera-based monitoring and evaluating system which is indeed able to track travelled distance, speed, direction changes, stationary time and spatial usage of individual ants and at colony level; spatial density, high-traffic areas and route repetition.

The research project should not focus on the fact that the ants can be detected in video recordings, rather how accurately and under which environmental conditions (such as illumination , background and ant density) their trajectories can be reconstructed automatically (including different approches for tracking), and what measureable behavioural patterns can be detected from the resulting trajectories.

## Why I am a good fit for this project
This project is especially relevant to me because my ColonyWatch project focuses on ant colonies, route adaptation, movement recording, and producing information from this collected data. And especially, my strong interest in ants and ant keeping makes me a strong candidate for this project.

I am interested in the complete process: designing repeatable experiments, collecting and annotating video data, implementing the detection and tracking systems, validating the results. I also see that occlusions, identity switches, annotation uncertainity, and experimental bias are more important parts of the system.

## Relevant experience and background
I have worked with Java,C# , Python, C, web programming, databases, software design, and computer networks. In ColonyWatch, I developed a modular Java/SpringBoot backend for sensor readings and historical data, including persistence, services, controllers, and automated tests using Maven and JUnit. This experience would help me to build the data processing part of the described system and store detections, trajectories and experimental results in a structured way.

## Proposed approach
I would first define a repeatable recording and annotation protocol and create a Python dataset from ant farm videos. I would record the colony before and after introducing a controlled water barrier that blocks an established route while leaving alternative dry routes available. The recordings would be devided into training, model selection, and final evaluation sets, with manually verified ant positions and identities used as reference.

I would then implement and compare two Python pipelines: an OpenCV based detection and tracking system and a machine learning detector combined with an identity tracking system. I would examine detection accuracy, identity switches and interrupted trajectories with special attention to occlusions and dense formations. After selecting the more reliable approach, I would reconstruct two dimensional tracks and calculate distance, speed and direction changes etc. 

Finally, I would visualise prefferred routes and compare the experimented route changes with an Ant Colony Optimization simulation.

My very last suggestion would be ; implementing the pipelines with multiple cameras and comparing the resulting accuracy and bias with the ones with single camera and depending on these evaluations, choosing the right approach for camera placement.

## Initial plan
1. Define the research questions, experimental conditions, camera placement, coordinate system and annotation format.
2. Write the technical specification and define the hypotheses for the controlled route choice experiments.
3. Record default ant movement and movement after blocking and established route with water barrier while keeping alternative routes available.
4. Create a manually annotated dataset and divide the recordings into three parts as mentioned above.
5. Develop the video processing pipeline and prototype ant detection and individual tracking.
6. Develop and compare an OpenCV based method with a ML detection and tracking method.
7. Reconstruct two dimentional trajectories, calculate individual and colony level movement indicators, visualise the preferred routes and the high traffic zones.
8. Evaluate the results against the manually verified reference data and document the effects of environmental conditions.
9. Taking the project to TDK.

## Additional information
I plan to maintain a Git repository from the beginning and use issues to organise the research and implementation tasks. The project will use suitable tools for video processing, data handling, ML, trajectory examination, and visualisation.

A link to my personal project ColonyWatch : https://github.com/YusufAtakanA/ColonyWatch
