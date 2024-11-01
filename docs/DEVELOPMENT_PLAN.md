# Development Plan for RedArc

## Project Overview

RedArc is designed to track the trajectory of a cricket ball from pre-recorded video footage. The PoC will focus on detecting the red ball against a stable background and plotting its path. Future iterations will focus on real-time analysis, cloud processing, and extended metrics.

## Development Phases

### Phase 1: Setup and Basic Detection
- Objective: Set up the environment and use OpenCV to detect a red ball in video footage.
- Expected Outcome: Ability to isolate the ball in frames and store coordinates in JSON format.

### Phase 2: Trajectory Tracking
- Objective: Implement tracking to follow the detected ball across frames.
- Expected Outcome: Basic trajectory path saved to JSON and optionally overlaid on video.

### Phase 3: Testing and Validation
- Objective: Test with varied footage and fine-tune detection for different conditions.
- Expected Outcome: Consistent detection across different cricket footage scenarios.

### Phase 4: Docker and Kubernetes Deployment
- Objective: Containerize the project and deploy to GCP Kubernetes for scalable processing.
- Expected Outcome: Cloud-deployed container capable of processing video files on GCP.

For more technical details, refer to the `DESIGN_OVERVIEW.md`.
