---
name: Yusuf Atakan AKYUZ
neptun: OKG649
id: 2026-ST-04
github: https://github.com/YusufAtakanA/project-course
github_project: https://github.com/users/YusufAtakanA/projects/2
---
# Camera-Based Monitoring, Automatic Tracking, and Route-Behaviour Analysis of Ant Colony Individuals

Ants reinforce frequently used routes with pheromone signals, and this is central to how a colony coordinates its movement without central control. This project uses a multi-camera observation approach to monitor ant movement in a controlled ant farm. It identifies and tracks individual ants over time, reconstructs their movement trajectories, and uses the observed routes to estimate the spatial distribution and relative intensity of pheromone trails. The estimate is an indirect representation of chemical signaling activity, not a direct measurement of pheromone concentration. The estimated trails are then used to predict the path an individual ant will take. The project also investigates how reliable tracking and trajectory reconstruction are under different observation conditions, and compares alternative approaches by tracking accuracy and computational efficiency.

## Objectives
- **Primary objective:** Identify and track individual ants over time, reconstruct their movement trajectories, and use the observed routes to estimate the spatial distribution and relative intensity of pheromone trails.
- **Target users / stakeholders:** Researchers studying ant behavior and swarm intelligence.
- **Measurable success criteria:** Using multi-camera recordings of the ant farm, the system saves a trajectory for each tracked ant, shows the frequently used pathways and an estimated pheromone trail map, predicts the path of a selected ant from the estimated trails, and reports the tracking accuracy and computational efficiency of two alternative approaches under different observation conditions.
- **Constraints:** Real ants in a controlled ant farm; multi-camera observation in 2D; pheromone trails are estimated from movement, not measured chemically; the surface the ants walk on is cleaned with 70% ethanol before each observation session, and each session is assumed to start with no pheromone trails.

## Scope

### In scope

- Multi-camera observation of ant movement in a controlled ant farm.
- Identifying and tracking individual ants over time and reconstructing their movement trajectories.
- Analysis of movement frequency, direction, and temporal patterns to identify frequently used pathways.
- Estimation of the spatial distribution and relative intensity of pheromone trails from the observed routes.
- Prediction of the path of an individual ant from the estimated pheromone trails.
- Investigation of how collective movement may contribute to trail formation and reinforcement.
- Reliability of tracking and trajectory reconstruction under different observation conditions.
- Comparison of alternative approaches by tracking accuracy and computational efficiency, to assess their suitability for continuous behavioral observation.

### Out of scope

- Direct chemical measurement of pheromone concentration.
- Simulated ants or simulated colony behavior.
- 3D reconstruction and physical marking of ants.
- Building a computational swarm-intelligence model; the findings may support such work later.

## Notes

 The algorithms, the pheromone estimation calculation, and the technical design are decided in the second half of the semester.
