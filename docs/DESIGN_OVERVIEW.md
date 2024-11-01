# Design Overview of RedArc

## Architecture Overview

RedArc will be based on a modular architecture, leveraging OpenCV for video processing, and using Docker + Kubernetes for cloud deployment.

## Core Components

1. **Ball Detection**:
    - Implements color masking and blob detection using OpenCV to locate the red cricket ball.

2. **Trajectory Tracking**:
    - Uses a tracking algorithm to follow the ball across frames, storing position data in JSON format.
    - Outputs a polyline overlay on video, visualizing the ball’s path.

3. **Cloud Deployment**:
    - The Python application will be containerized with Docker and deployed on Kubernetes (GCP) for processing multiple videos.

## Future Enhancements
- Add speed and spin metrics to the trajectory.
- Integrate real-time streaming capabilities from the Raspberry Pi to the cloud.
- Extend the system to handle different lighting conditions and non-standard camera angles.

See `DEVELOPMENT_PLAN.md` for detailed phases and milestones.
