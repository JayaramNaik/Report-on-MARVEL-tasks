### Task 2: ***Building API*** 

I built a simple API that fetches and displays the "Astronomy Picture of the Day" using NASA's APOD API. This project helped me understand how to make API calls, handle JSON data, and manage asynchronous operatIons.   [Assignment 02 API](
https://jayaramnaik.github.io/Assignment-02-API-/)

### TASK 3:           **GitHub Repository:** 

For this task, I gained practical experience with essential Git workflows by cloning a repository, creating a new branch, and fixing an error. I then used a pull request to contribute my changes, which provided hands-on experience with **GitHub Actions**, **Issues**, and **Pull Requests**.

**GitHub Actions Run:** [https://github.com/UVCE-Marvel/git-task/actions/runs/17120134091](https://github.com/UVCE-Marvel/git-task/actions/runs/17120134091)

### TASK 4: ###
### **Command Line Operations**

### **Command Line Operations Report**

I familiarized myself with commands and Ubuntu by completing a series of fundamental tasks. This included **directory and file management**, **efficiently creating 2600 subdirectories** using a loop, and **concatenating two text files** to display their content. The project demonstrates a practical understanding of core command-line operations.![alt text](<WhatsApp Image 2025-08-21 at 12.53.08_377a13d2-1.jpg>)


# 📊 Task 5: Build Your Own Brain – Linear Regression from Scratch

## 1. Objective
The aim of this task was to understand and implement the concept of **Linear Regression** from scratch using **Gradient Descent**, and to **compare its performance** with the inbuilt `LinearRegression` model from **scikit-learn** on the **California Housing dataset**.

---

## 2. Introduction
Linear Regression is one of the simplest and most fundamental supervised machine learning algorithms used for predicting continuous values. It establishes a linear relationship between the input features (X) and the target variable (y).

**Gradient Descent** is an optimization algorithm used to minimize the cost function by iteratively updating the model weights in the opposite direction of the gradient.

---

## 3. Methodology

### 3.1 Dataset
- Dataset used: **California Housing Dataset** from `sklearn.datasets`
- It consists of various housing-related features like:
  - Median income
  - House age
  - Average number of rooms, bedrooms, population
  - Latitude and longitude  
- Target variable: **Median House Value**

### 3.2 Data Preprocessing
- Loaded the dataset and converted it into a Pandas DataFrame
- Split data into training and testing sets (80:20)
- Applied **feature scaling (Standardization)** to improve gradient descent convergence speed

### 3.3 Custom Linear Regression Implementation
- Implemented the hypothesis function:  
  \[
  \hat{y} = XW + b
  \]
- Defined the cost function (Mean Squared Error):
  \[
  J(W,b)=\frac{1}{n}\sum_{i=1}^{n} (\hat{y}_i - y_i)^2
  \]
- Used **Gradient Descent** algorithm to update weights:
  \[
  W := W - \alpha \frac{\partial J}{\partial W}
  \]
  \[
  b := b - \alpha \frac{\partial J}{\partial b}
  \]
- Iteratively updated weights until convergence (for around 1000 epochs, learning rate ≈ 0.01)

### 3.4 Scikit-learn Linear Regression
- Imported `LinearRegression` from `sklearn.linear_model`
- Trained the model using the same training data
- Predicted target values on the test set

---

## 4. Results & Analysis

### 4.1 Performance Metrics

| Model                          | MSE (↓) | MAE (↓) | R² (↑) |
|-------------------------------|---------|---------|---------|
| Custom Linear Regression      | ~0.55   | ~0.47   | ~0.62   |
| Scikit-learn LinearRegression | ~0.52   | ~0.45   | ~0.64   |

*(Note: The values are approximate and may vary slightly depending on train-test split and hyperparameters.)*

### 4.2 Visualization
- Plotted the predicted vs actual values for both models
- Plotted the **line of best fit** for a single feature (e.g., median income vs median house value) along with the data points
- Observed that both models showed similar trends, but the scikit-learn model converged faster and produced slightly better results

---

## 5. Comparison Between Custom and Scikit-learn Models

| Aspect                | Custom Implementation         | Scikit-learn          |
|------------------------|-------------------------------|-------------------------|
| Training Speed         | Slow (due to manual GD)       | Very Fast               |
| Accuracy               | Slightly lower                 | Higher                  |
| Effort                 | Requires more coding & tuning | Minimal                 |
| Flexibility             | Fully customizable             | Predefined               |
| Learning Value          | High (builds core understanding) | Moderate            |

---

## 6. Key Learnings
- Understood how **gradient descent** optimizes weights by minimizing cost
- Learned the **importance of feature scaling** for faster convergence
- Gained experience in implementing **core ML concepts from scratch**
- Appreciated the **efficiency and ease of use of inbuilt ML libraries**
- Understood how to evaluate models using **MSE, MAE, and R²**

---

## 7. Conclusion
Building a linear regression model from scratch helped to deeply understand how machine learning algorithms work internally. While the custom model gave reasonably good results, the scikit-learn model was faster, more accurate, and much easier to use. This task highlighted the balance between **understanding fundamentals** and **using optimized libraries** in real-world projects.

# 🧩 Task 6: The Matrix Puzzle — Decode with NumPy & Reveal the Image

## 1. Objective
The aim of this task was to **decode a scrambled matrix** using **NumPy operations** and then **visualize the hidden image** using `matplotlib.pyplot.imshow()`.  
This task helped build practical understanding of array manipulation, reshaping, orientation correction, and visualization in Python.

---

## 2. Introduction
**NumPy** is a powerful library for numerical computing in Python, providing efficient operations on large multidimensional arrays.  
**Matplotlib** is a widely used plotting library that allows visualization of numerical data, including images.

This task involved:
- Analyzing a scrambled numerical matrix
- Identifying its correct structure and orientation
- Applying suitable NumPy transformations to recover the hidden image

---

## 3. Methodology

### 3.1 Dataset
- A scrambled matrix was provided as a `.npy` or similar data file.
- Loaded it using `numpy.load()`.

### 3.2 Exploration & Analysis
- Used `.shape`, `.size`, `.dtype` to understand the structure of the matrix.
- Verified the total number of elements.
- Based on the hint:  
  - “Try reshaping the encoded array into a square—how many elements are there?”  
  - Calculated the square root of the number of elements to find the possible side length.

### 3.3 NumPy Operations Applied
- **Reshaping**:  
  ```python
  reshaped = scrambled.reshape(n, n)


![alt text](<WhatsApp Image 2025-09-12 at 20.44.45_296b658c.jpg>)

# Task 7: Portfolio Webpage

## Objective
To create a personal portfolio webpage using HTML to display my details, interests, and projects, and upload it to a GitHub repository.

---

## Tools Used
- HTML  
- Git & GitHub  

---

## Features
- About Me section  
- My Projects  
- Social media/contact links  

---

## Outcome
A basic portfolio webpage created using only HTML and hosted on my GitHub repository.

---

## GitHub Link
[View Portfolio Repository](https://github.com/JayaramNaik/PORTFOLIO.git)

# Task 8: Resource Article

## Title
**Sustainable Technology (Green Tech): A Detailed Look**

## Description
A detailed resource article on **Sustainable Technology (Green Tech)** — exploring **green computing**, **sustainable data centers**, and **tech-driven solutions to combat climate change**.
# Resource-Article
A detailed resource article on Sustainable Technology (Green Tech) — exploring green computing, sustainable data centers, and tech-driven solutions to combat climate change.
## GitHub Link
[View resource article](https://github.com/JayaramNaik/Resource-Article.git)

# Task 9: Tinkercad — Ultrasonic Sensor Radar System

## Objective
To understand and use Tinkercad to simulate circuits and build a simple radar system using an ultrasonic sensor and a servo motor to detect objects and display distances on the serial monitor.

---

## Tools Used
- **Tinkercad** (Online circuit simulator)
- **Ultrasonic Sensor (HC-SR04)**
- **Servo Motor**
- **Arduino UNO Board**
- **Serial Monitor (in Tinkercad)**

---

## Procedure
1. **Created a Tinkercad account** and explored the interface.
2. **Studied example circuits** available in Tinkercad to understand basic connections and Arduino coding.
3. **Built a simple distance measuring circuit** using an ultrasonic sensor to estimate the distance of an obstacle.
4. **Wrote Arduino code** to calculate distance and display it on the serial monitor.
5. **Enhanced the setup** by adding a servo motor.
6. **Programmed the servo motor** to rotate the ultrasonic sensor to cover a wider area like a radar.
7. **Observed real-time distance values** on the serial monitor while the servo rotated the sensor.

---

## Working Principle
- The **ultrasonic sensor** emits sound waves and measures the time taken for them to bounce back from an object to calculate distance.  
- The **servo motor** rotates the ultrasonic sensor to scan across a range of angles.  
- This mimics a **basic radar system**, which can detect objects within its scanning range.

---

## Task Outcome
- Introduction to **Tinkercad** platform and its simulation features  
- Understanding of **ultrasonic sensor** and **servo motor** working  
- Basic concept of **radar technology** using Arduino simulation  

---
## GitHub Link
[View in tinkercad](https://www.tinkercad.com/things/1tBj07HIGD8/editel?returnTo=%2Fdashboard&sharecode=rDVwI35YMyzfKWHe3xc3TQXbpTRt9bYp3MAbv7DcguQ)

# Task 10: Speed Control of DC Motor

## Objective
To control the speed of a 5V BO DC motor using an Arduino UNO and an L298N motor driver by applying PWM signals. The circuit was first simulated on Tinkercad and then implemented on hardware.

---

## Components
- Arduino UNO  
- L298N Motor Driver  
- 5V BO DC Motor  
- Jumper wires, breadboard  

---

## Steps
1. Connected the motor to the L298N driver and interfaced it with Arduino.  
2. Used `analogWrite()` on the enable pin to vary motor speed.  
3. Simulated the setup on Tinkercad.  
4. Built and tested it on hardware.

---

## Outcome
- Learned to control motor speed using PWM.  
- Understood the working of the L298N motor driver.  
- Practiced simulation on Tinkercad and real hardware setup.

---

## Reference
[L298N Motor Driver Basics](https://www.makerguides.com/l298n-dc-motor-driver-arduino-tutorial/)
## Vedio link [Watch here](https://photos.app.goo.gl/xbL84d6n9ETgjbSL9)


# Task 11: LED Toggle Using ESP32

## Objective
To learn the working of an **ESP32 microcontroller** and create a **standalone web server** using Arduino IDE to control an LED connected to an ESP32 GPIO pin.

---

## Tools & Components
- ESP32 Development Board  
- LED and Resistor  
- Arduino IDE  
- USB Cable and Wi-Fi network

---

## Steps
1. Installed ESP32 board support in Arduino IDE through **Board Manager**.  
2. Connected the ESP32 to the computer via USB and selected the correct **board and port**.  
3. Wrote code to create a **web server on the ESP32**.  
4. Configured GPIO pin as **output** and added functions to **toggle LED state** from the webpage.  
5. Uploaded the code to ESP32 and accessed the local web server through the given IP address.  
6. Successfully controlled the LED by clicking buttons on the webpage.

---

## Outcome
- Understood the **working of ESP32** and its **GPIO control**.  
- Learned to **configure Arduino IDE** for ESP32.  
- Created a **basic IoT application** using a standalone ESP32 web server.

---
## Vedio link  [Watch here](https://photos.app.goo.gl/wNxyAq8L7rTdUwRi9)

# Task 12: Soldering Prerequisites

## Introduction
Soldering is a fundamental skill in electronics used to make permanent electrical connections between components. This task involved learning about the basic soldering tools present in our lab and performing a simple soldering activity under the supervision of a coordinator.

---

## Soldering Equipment Learned
- **Soldering Iron** – Heats the solder to join electronic components.
- **Solder Wire** – A fusible metal alloy used to create the joint between parts.
- **Flux** – Helps remove oxidation and improve solder flow.
- **Soldering Wick / Desoldering Pump** – Used to remove excess solder.
- **Perf Board (Prototype Board)** – A board used to mount and connect components.

---

## Activity Performed
- Identified and learned the correct use of soldering tools.
- Practiced safe handling of the soldering iron.
- Soldered a simple **LED circuit** on a perf board (LED, resistor, power connections).
- Ensured all joints were firm and had no loose connections.

---

## Outcome
- Gained hands-on experience in **basic soldering techniques**.  
- Understood the use and purpose of **common soldering tools**.  
- Learned **safety precautions** to be followed while soldering.

---
![
](<WhatsApp Image 2025-09-14 at 23.57.09_bb5e5c03.jpg>)

# TASK 14: Karnaugh Maps & Logic Circuit (Burglar Alarm)

## Objective
To design a simple burglar alarm that triggers **only when the door is open (D=1) and the key is not pressed (K=0)**, using logic circuits or Arduino.

---

## Danger Condition
- Inputs:
  - `D` = Door state (1 = open, 0 = closed)  
  - `K` = Key state (1 = pressed, 0 = not pressed)  
- Alarm triggers only when:  
  **D = 1 AND K = 0**

---

## Boolean Expression


![alt text](image-3.png)

# Task 15: Synthetic Intelligence Competition

Participated in a **Synthetic Intelligence competition** focused on **prompt engineering**. Gained hands-on experience in designing effective prompts for AI models and learned how well-structured prompts can influence AI responses.

![alt text](image-4.png)

# Task 16 # Datasheet Report: L293D Motor Driver IC  

The *L293D* is a quadruple half-H driver IC designed to drive inductive loads like DC motors, stepper motors, and relays.  
It's widely used in robotics and automation projects due to its ability to control the direction and speed of two DC motors simultaneously.  

- *Operating Voltage:* 4.5 V – 36 V  
- *Output Current:* Up to 600 mA per channel (continuous)  

---

## Internal Structure and Key Concepts  

The L293D contains *four independent drivers, each being a **half-H bridge*.  
- Drivers are enabled in pairs (1 & 2, and 3 & 4), allowing control of *two separate motors*.  
- Each driver uses a *Darlington transistor sink* and a *pseudo-Darlington source*, amplifying small control signals from a microcontroller.  
- The *“D”* in L293D indicates built-in *output clamp diodes* for protection against voltage spikes from inductive loads.  

---

## H-Bridge  

An *H-bridge* is an electronic circuit that lets current flow through a load (like a DC motor) in either direction.  

- Shape resembles *‘H’*.  
- Consists of *four switches (transistors)*.  
- By toggling switch pairs, the motor can spin *forward or backward*.  

➡ The *L293D has two H-bridges, so it can control **two motors independently*.  

---

## PWM (Pulse Width Modulation)  

*PWM* controls motor speed by rapidly turning power *on and off*.  

- Motor speed ∝ *average voltage* supplied.  
- *Duty Cycle:* percentage of time the signal is ON.  
  - Example:  
    - *90% ON* → High speed  
    - *20% ON* → Low speed  

The *L293D enable pins* accept PWM signals for *speed control*.  

---

# Datasheet Report: MQ-135 Gas Sensor  

The *MQ-135* is a semiconductor gas sensor used for *air quality monitoring*.  
It detects:  
- Ammonia (NH₃)  
- Carbon dioxide (CO₂)  
- Benzene  
- Alcohol  
- Smoke  

# Task 17 
# Report: Introduction to Virtual Reality (VR) and Augmented Reality (AR)

#### What is Virtual Reality (VR)?

Virtual Reality (VR) is a technology that creates a simulated, three-dimensional, computer-generated environment that a user can interact with as if it were real. The primary goal of VR is to achieve a sense of "presence," or a feeling of being physically in a new, different world. This is achieved by completely immersing the user's senses (primarily sight and sound) through specialized hardware, most commonly a head-mounted display (HMD) and controllers. The HMD blocks out the real world and projects a virtual one, and motion tracking sensors track the user's head and body movements, allowing them to look around and navigate the virtual space naturally.

#### What is Augmented Reality (AR)?

Augmented Reality (AR) is a technology that overlays digital information, such as images, videos, 3D models, and text, onto the user's view of the real world. Unlike VR, AR does not replace the real environment; instead, it enhances it. The user remains fully aware of their physical surroundings while the digital elements are integrated into their perception. AR can be experienced through various devices, including smartphones, tablets, and specialized AR glasses. A common example is the popular game Pokémon Go, where digital Pokémon appear to be in the real world through a smartphone's camera.

#### Detailed Comparison: VR vs. AR

| Feature | Virtual Reality (VR) | Augmented Reality (AR) |
|---|---|---|
| *Immersion* | Creates a fully immersive, simulated environment, replacing the user's view of the real world. | Overlays digital content onto the user's view of the real world, enhancing their perception. |
| *User Experience* | Aims to transport the user to a different reality, completely disconnecting them from their physical surroundings. | Blends virtual content with the real world, allowing the user to interact with both at the same time. |
| *Hardware* | Typically requires a dedicated headset (e.g., Meta Quest, Valve Index) with a fully enclosed display that blocks outside light. | Can be accessed through a wide range of devices, including smartphones, tablets, and transparent smart glasses (e.g., Microsoft HoloLens). |
| *Interaction* | Interaction is limited to the virtual environment and often requires specialized controllers or hand-tracking devices. | Allows for interaction with both virtual objects and the physical objects in the immediate surroundings. |
| *Use Cases* | Primarily used for gaming, immersive training simulations (e.g., medical, military), virtual tours, and entertainment. | Found in applications like retail (virtual try-ons), education (overlaying information on real objects), and field service (remote assistance). |

#### Trends in the VR/AR Space and Technology Stack Development

The VR and AR landscape is rapidly evolving, driven by advancements in hardware and software.

*Latest Trends:*

* *Integration of AI and Machine Learning:* AI is being used to create more realistic and interactive virtual environments, personalize experiences, and enable more natural interactions through computer vision and natural language processing.
* *WebAR and Cross-Platform Compatibility:* Developers are increasingly using WebAR (AR experiences accessible through a web browser) to make AR more accessible without requiring a dedicated app download. This trend focuses on a smoother user experience and broader reach.
* *5G Integration:* The advent of 5G networks is crucial for VR/AR. The high speed and low latency of 5G enable more responsive and high-definition experiences, particularly for cloud-based rendering and real-time multiplayer applications.
* *Haptic Technology:* Haptic feedback gloves and suits are being developed to add the sense of touch to VR experiences, further enhancing immersion for training, gaming, and design.
* *Enterprise Adoption:* While gaming remains a key sector, industries like healthcare (surgical simulation, therapy), manufacturing (design visualization, remote maintenance), and education (virtual classrooms) are increasingly adopting VR and AR for training and operational efficiency.

*Technology Stack:*

The development of VR and AR applications relies on a robust technology stack, including:

* *Game Engines:* *Unity* and *Unreal Engine* are the most popular development platforms. They provide the core tools for building 3D environments, handling physics, and rendering graphics.
* *Platform-Specific SDKs:*
    * *Google ARCore* and *Apple ARKit* are essential for developing AR applications for Android and iOS devices, respectively. They handle motion tracking, environmental understanding, and light estimation.
    * For VR, platforms like the *Oculus SDK* (for Meta Quest headsets) and *SteamVR* (for a variety of headsets) provide tools for tracking and interaction.
* *Hardware:* The stack includes the physical devices themselves, from high-end VR headsets like the *Meta Quest* and *Valve Index* to mobile devices for AR.
* *3D Modeling and Design Tools:* Software like *Blender, **Autodesk Maya, and **ZBrush* is used to create the 3D assets, characters, and environments that populate the virtual and augmented worlds.

#### Indian Companies in the VR/AR Space

India's VR and AR ecosystem is growing, with several companies and startups making significant contributions.

* *Tata Elxsi:* A prominent player in the Indian tech scene, Tata Elxsi offers design and engineering services for extended reality (XR) solutions. They work with various industries to create immersive training programs, product showcases, and VR experiences.
* *Simulanis:* This company specializes in providing VR and AR-based training and simulation solutions for the industrial sector. Their products include simulators for welding, spray painting, and field force productivity, helping businesses improve efficiency and safety.
* *Imaginate:* Based in Hyderabad, Imaginate offers custom VR and AR solutions for enterprises. They focus on creating immersive content for training, remote collaboration, and product support across industries like manufacturing, oil and gas, and healthcare.
* *AjnaLens:* An Indian startup that designs and manufactures its own mixed reality headsets. They target the defense and enterprise sectors with hardware and software solutions aimed at improving productivity and training.
* *PlayShifu:* This company has gained recognition for its innovative AR-based educational toys. Their products, such as the Orboot globe, merge physical toys with AR to create interactive learning experiences for children.
* *Trezi:* This company provides a unique VR and AR platform for the architecture, engineering, and construction (AEC) industry. Trezi allows architects and designers to visualize building plans in an immersive, real-time environment, streamlining the design process.
* *AutoVRse:* Based in Bengaluru, AutoVRse creates custom VR/AR applications for various industries, including energy, manufacturing, and real estate. They specialize in building bespoke training simulations and virtual factory tours.

![
](<WhatsApp Image 2025-09-15 at 00.23.34_96049144.jpg>)

# Task 19: Resource Library Web App

## Objective
To create a **resource library website** where users can browse articles, books, and other learning materials. The project focuses on the front-end design using **HTML only**.

---

## Tools Used
- HTML  
- Git & GitHub  

---

## Features Implemented
- Browse available resource articles and books  
- Basic account management layout (no backend functionality)  
- Structured and navigable web pages

---

## Outcome
- Designed a simple and organized front-end for a resource library.  
- Practiced HTML structuring, navigation, and linking pages.  
- Project hosted on GitHub.

---

## GitHub Repository
[View Repository](https://github.com/JayaramNaik/Resource-library.git)

# Task 21: Introduction to Machine Learning

## Overview
This article summarizes the foundational concepts of **Machine Learning (ML)** and data preparation techniques based on two beginner-friendly videos:

1. *A Gentle Introduction to Machine Learning* by StatQuest  
2. *How is Data Prepared for Machine Learning?* by AltexSoft

---

## Key Concepts from "A Gentle Introduction to Machine Learning"
- **Definition**: Machine Learning is a subset of artificial intelligence where computers learn patterns from data to make predictions or decisions without being explicitly programmed.  
- **Types of ML**: 
  - **Supervised Learning**: Models learn from labeled data to predict outcomes.  
  - **Unsupervised Learning**: Models find patterns or groupings in unlabeled data.  
  - **Reinforcement Learning**: Models learn by trial and error through rewards and penalties.  
- **Applications**: Image recognition, spam detection, recommendation systems, and more.

---

## Key Concepts from "How is Data Prepared for Machine Learning?"
- **Data Collection**: Gathering relevant and sufficient data is the first step.  
- **Data Cleaning**: Removing errors, missing values, and inconsistencies to ensure quality input.  
- **Feature Selection & Engineering**: Choosing important variables and transforming data into a format suitable for ML models.  
- **Data Splitting**: Dividing data into training, validation, and test sets to evaluate model performance.

---

## Reflections
- Proper **data preparation** is as important as choosing the right algorithm.  
- Understanding different **types of ML** helps in selecting the appropriate approach for a problem.  
- ML models are most effective when combined with **clean, well-structured data**.  
- Watching these videos reinforced the importance of starting simple, understanding the concepts, and gradually moving to more complex ML tasks.

---

## Conclusion
Machine Learning is a powerful tool to derive insights from data, but its success heavily relies on **data quality** and **understanding foundational principles**. Beginner-friendly resources like the videos above provide a clear pathway to start learning and applying ML concepts effectively.




