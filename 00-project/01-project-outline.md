---
name: Yusuf Atakan AKYUZ
neptun: OKG649
id: 2026-ST-04
github: https://github.com/YusufAtakanA/project-course
trello:
---
#  Camera-Based Monitoring, Automatic Tracking, and Route-Behaviour Analysis of Ant Colony Individuals

This project develops an application that detects multiple real ants, assigns temporary identities to reliable track segments, and records their movement over time. The registered segments support route analysis and an estimate of relative pheromone-trail intensity without requiring permanent identity for every ant. Multiple cameras support clearer, more detailed observation of a two-dimensional environment. Two algorithms will be compared using manually verified recordings, including tracking accuracy and elapsed processing time.

## Objectives
- **Primary objective:** Track multiple ants simultaneously, save their paths, and estimate relative pheromone-trail intensity from the registered tracks.
- **Target users / stakeholders:** Researchers studying ant movement and route usage.
- **Measurable success criteria:** The application saves distinguishable tracks with timestamps and direction, displays an estimated trail-intensity map with observation coverage, identifies missing-data gaps, and reports a comparison of two algorithms.
- **Constraints:** Real-ant observations; 2D analysis; limited annotation time; explicit uncertainty and missing-data handling.

## Scope

### In scope

- Recorded video from one or multiple cameras for detailed 2D observation.
- Detection, temporary track identities, and simultaneous tracking of multiple ants.
- Saved tracks, travel direction, movement measurements, and route analysis.
- Relative pheromone-trail intensity estimated from observed tracks.
- Camera/time coverage, missing-data gaps, and prevention of duplicate counting in overlapping views.
- Manually verified reference data and comparison of two algorithms, including wall-clock processing time.

### Out of scope

- Simulated ants, simulated colony behaviour, and Ant Colony Optimization simulation.
- 3D reconstruction, physical marking, and automatic physical control of the colony.
- Direct chemical measurement of pheromone concentration or independent biological causal validation.
- Guaranteed permanent identity for every ant across the entire observation session.

## Notes

Live monitoring and longer-term identity continuity are possible additions, to be decided after feasibility is assessed. The trail-intensity output is a movement-based estimate, with its assumptions and missing coverage made visible. Specific algorithms and the estimation calculation will be discussed later in the semester.


