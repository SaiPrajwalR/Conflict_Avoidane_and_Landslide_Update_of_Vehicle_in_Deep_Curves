🌧️🚘**Conflict Avoidance and Landslide Update of Vehicle in Deep Curves**

📖 Overview The IoT-Based Conflict Avoidance and Landslide Detection System is an intelligent road safety solution designed for deep curves, blind bends, and landslide-prone hilly areas. This system combines IoT, Embedded Systems, and sensor-based automation to provide real-time vehicle monitoring, landslide detection, and automated traffic control. It helps reduce head-on collisions, improves driver safety, and provides early hazard warnings with minimal human intervention.

🚀 Features

🔍 Smart Monitoring
  • Vehicle Detection using IR Sensors
  • Landslide Detection using ADXL345 Accelerometer
  • Rainfall Monitoring using Rain Sensor
  • Real-time Environmental Monitoring

⚙ Automation
  • Automatic Traffic Control using Motorized Gates
  • Real-time processing using Arduino Uno
  • Intelligent traffic signal management using LEDs

🚨 Safety System
  • Real-time hazard alerts using LCD Display and Buzzer
  • Instant detection of:
  • Landslides
  • Heavy Rainfall
  • Vehicle conflicts in blind curves

🛠 Technologies Used
  Category : Technology
  Hardware : Arduino Uno, IR Sensors, ADXL345, Rain Sensor, Zigbee
  Embedded : Arduino IDE, Embedded C
  Communication : Zigbee Wireless Communication
  Display & Alerts : LCD Display, Buzzer, LEDs
  Automation : DC Motors, Motor Driver

🏗 System Architecture
  IR sensors detect approaching vehicles from both sides
  ADXL345 monitors vibration and ground tilt
  Rain sensor monitors rainfall intensity
  Arduino Uno processes all sensor data
  System automatically:
  • Controls traffic signals
  • Opens/Closes gates
  • Sends hazard alerts
  • Displays real-time information

📂 Project Structure
  LANDSLIDE/
  │── __pycache__/            # Cached Python files
  │── data/                   # Dataset and configuration files
  │── models/                 # Model architecture files
  │── runs/                   # Training and detection outputs
  │── utils/                  # Utility/helper functions
  │
  │── .gitignore              # Git ignored files configuration
  │── benchmarks.py           # Model benchmarking script
  │── detect.py               # Object/crack detection script
  │── export.py               # Model export script
  │── requirements.txt        # Required Python libraries
  │── serial_test.py          # Serial communication testing
  │── train.py                # YOLOv5 model training script
  │── val.py                  # Model validation script
  │── yolov5s.pt              # Pre-trained YOLOv5 model weights

📊 Results
  • Successful vehicle detection in deep curve regions
  • Accurate landslide and rainfall monitoring
  • Automated gate response during hazardous conditions
  • Reduced risk of head-on collisions
  • Improved road safety and traffic management

👨‍💻 Team Members
  • Sai Prajwal R
  • Yeshwanth K
  • Vikas R Hirematha
  • Bhojaraja D S

🎓 Project Guide
  Dr. J. Sebastian Nixon
  Professor, Department of Computer Science & Engineering

🔮 Future Scope
  • Cloud-based monitoring system
  • GPS integration for live hazard updates
  • AI-based landslide prediction
  • Mobile application for remote monitoring
  • Large-scale smart highway integration

📜 License 

This project is developed for academic purposes under Dayananda Sagar University.
