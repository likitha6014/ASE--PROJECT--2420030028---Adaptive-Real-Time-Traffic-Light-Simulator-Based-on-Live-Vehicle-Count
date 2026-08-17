# Adaptive Real-Time Traffic Light Simulator Based on Live Vehicle Count

## Team Members

| S. No. | University ID | Name |
|--------|---------------|------|
| 1 | 2420030028 | P. Likhitha |
| 2 | 2420030076 | G. Karthika |
| 3 | 2420030671 | K.L Manasa |
| 4 | 2420030677 | J. Vardhini |

**Name of the Guide:** Swapna Reddy

---

## Abstract

The **Adaptive Real-Time Traffic Light Simulator Based on Live Vehicle Count** is a smart traffic management system developed to improve the efficiency of traffic signals at road intersections. In conventional traffic signal systems, the green-light duration is usually fixed and does not change according to the actual traffic conditions. This can cause unnecessary waiting time, traffic congestion, fuel consumption, and delays, particularly when one road has significantly more vehicles than another.

The proposed system addresses this problem by dynamically controlling traffic signal timings based on the real-time vehicle count on each road. Vehicle counts can be obtained using sensors, cameras, or a simulated vehicle detection module. The collected data is analyzed to determine the traffic density of each lane. Based on this information, the system automatically assigns an appropriate green-light duration to each lane. Roads with higher vehicle density are given longer green-light periods, while roads with fewer vehicles receive shorter durations.

The simulator provides a visual representation of the intersection, including vehicles, traffic signals, vehicle counts, and dynamically changing signal timings. As the number of vehicles changes, the system continuously updates the signal sequence, allowing users to observe how adaptive traffic control responds to different traffic conditions. The system can also include minimum and maximum green-light limits to prevent any lane from being blocked for an excessive amount of time.

The main objective of this project is to demonstrate how real-time data and adaptive decision-making can be used to improve traffic management. The proposed approach can help reduce average vehicle waiting time, minimize unnecessary congestion, improve traffic flow, and potentially reduce fuel consumption and emissions caused by vehicles waiting at signals. The simulator also provides a basic platform for understanding intelligent transportation systems and can be further enhanced using IoT devices, computer vision, machine learning, and live traffic data.

Overall, the project demonstrates that adaptive traffic signals based on live vehicle count can provide a more flexible and efficient alternative to traditional fixed-time traffic signal systems. It can serve as a foundation for developing more advanced smart-city traffic management solutions in the future.

---

## Setup and Execution Instructions

1. Install Python and the required project dependencies (see `requirements.txt`).
2. Clone or download the project repository from GitHub.
3. Install or configure the YOLOv8n model used for vehicle detection.
4. Provide a traffic video, live camera input, or configured vehicle-count data as the source.
5. Run the vehicle-detection and counting module to process the input and identify vehicles per lane.
6. Start the Pygame traffic simulation to visualize adaptive signal control in real time.
7. (Optional) Use Docker to build and run the project in a containerized, consistent environment.
8. (Optional) Use MLflow to log and track machine-learning experiments, parameters, and metrics.

### Project Structure

- `main.py` – Main Python program.
- `vehicle_detection.py` – Vehicle detection/counting module, if separated.
- `simulation.py` – Pygame traffic simulation module, if separated.
- `models/` – YOLOv8n model files or model configuration, if required.
- `requirements.txt` – Python dependencies.
- `Dockerfile` – Docker configuration.
- `README.md` – Project documentation.

### Tools and Technologies

Python, OpenCV, YOLOv8n, Pygame, GitHub, Docker, Trello, MLflow.

---

## Current Phase Status

**Course:** Engineering Capstone Project – 1 (23IE4053R / 23IE4053A)
**Academic Year:** 2026 – 2027

**Status:** Phase 1 – Project Proposal and Abstract Submission completed. The project title, team, problem statement, objectives, system workflow, and adaptive traffic logic have been defined. Implementation of the vehicle detection, lane-wise density analysis, adaptive signal control, and Pygame simulation modules is in progress for the next phase.
