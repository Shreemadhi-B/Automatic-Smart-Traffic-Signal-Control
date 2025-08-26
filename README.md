# 🚦 Automatic Smart Traffic Signal Control  

Automatic-Smart-Signal is an **AI-based traffic control system** that uses **YOLOv5/YOLOv7/YOLOv8** to detect ambulances, estimate traffic density, and dynamically switch signals in real time. It enhances traffic flow efficiency with adaptive logic, reduces delays, and ensures faster emergency response by dedicating signals for ambulances.  

---

## Project Overview  
Urban traffic congestion is a growing problem, often leading to:  
- **Uncleared ambulance paths** delaying emergency care  
- **Long waiting times at signals** leading to inefficiency  
- **Unattended road accidents** increasing loss of life  

This project presents an **AI-powered Smart Traffic Signal Control System** that optimizes traffic management using **computer vision, IoT, and machine learning**. The system adapts signal timings based on real-time traffic data and prioritizes emergency vehicles by introducing a **dedicated emergency signal**.  

---

## Objectives  
- Enable **easy movement of ambulances** through major signals.  
- **Reduce loss of life** due to unattended accidents.  
- **Minimize waiting times** at traffic signals using adaptive control.  

---

##  Key Features  
-  **Dynamic Signal Timing** – Adjusts lights based on real-time density.  
-  **Emergency Vehicle Priority** – Detects ambulances via **YOLOv8**, siren detection, and GPS signals.  
-  **Dedicated Emergency Signal (Novelty)** – A **blue light** blinks to alert the public until the ambulance clears the junction.  
-  **Traffic Density Estimation** – Uses **YOLOv7** for fast, accurate density analysis.  
-  **Accident Detection & Alerts** – Detects accident severity (YOLOv7) and notifies via mobile app.  
-  **IoT + Cloud Integration** – Collects siren frequency, GPS, and camera inputs for decision-making.  
-  **Modular Workflow** – Separate scripts for training, validation, and prediction.  
-  **Interactive Notebook** – Hands-on demo of the pipeline.  

---

##  Proposed Solution  
- **Signal Switching** with adaptive AI logic.  
- **Ambulance Detection** using YOLOv8 + GPS app + siren frequency.  
- **Accident Detection** with YOLOv7 to classify accident severity.  
- **Mobile App** integration for notifications and GPS-based priority.  
- **Edge Deployment** for real-time intersection control.  

---

##  Novelty of the Project  
-  **Dedicated Emergency Signal**: Introduction of a **blue blinking light** for emergency vehicles, ensuring visibility and priority.  
-  **Multiple Confirmation Checks**: Ambulance detection is validated through **computer vision, GPS, and siren frequency** for higher reliability.  

---

## Emerging Technology Trends Used  
- **Computer Vision (YOLOv7/YOLOv8)** – Real-time vehicle, ambulance, and accident detection.  
- **Machine Learning** – Adaptive logic for signal switching.  
- **IoT** – Hardware integration with traffic lights for dynamic switching.  
- **Cloud Computing** – Siren frequency data processed in cloud and sent to AI model.  

---

##  Repository Structure  

.
├── train.py        # Train the traffic control model
├── val.py          # Validate the trained model
├── predict.py      # Predict traffic signal timings on new data
├── tutorial.ipynb  # End-to-end walkthrough in Jupyter
└── README.md       # Documentation


##  Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/smart-traffic-signal.git
   cd smart-traffic-signal
   

2. Install dependencies (Python 3.8+ recommended):

pip install -r requirements.txt

## Results

- Traffic Density Estimation – YOLOv7 achieved high FPS and accuracy.

- Emergency Vehicle Detection – YOLOv8 successfully detected ambulances in real time.

- Accident Detection – YOLOv7 classified severity of accidents for alerting.

- Signal Hardware Prototype – Implemented 2-way and 4-way circuits for signal switching.

## Future Enhancements

Integration with city-wide IoT traffic sensors & cameras.

Scaling to multi-intersection smart networks.

Reinforcement learning for self-optimizing signal cycles.

Full cloud + edge deployment for smart city adoption.

## License

This project is licensed under the MIT License – feel free to use and adapt.

## Author

Developed by Shreemadhi B – Passionate about YOLO, AI, IoT, and Smart City Solutions 🌍.
