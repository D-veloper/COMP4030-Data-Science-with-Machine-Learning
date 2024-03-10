# COMP4030-Data-Science-with-Machine-Learning

**Project Title: Recognition of Different Surface Terrains using a 6-Axis IMU**

### Introduction:
People with mobility disabilities face challenges, especially when navigating uneven terrains with assistive walking devices like a rollator. The goal of this project is to develop an AI-based system to assist individuals by detecting the type of surface they are walking or pushing the rollator on. The detection will be based on inertial measurement units (IMU), specifically utilizing accelerometer and gyroscope data from an Axivity sensor attached to the rollator.

### Project Overview:
- **Sensor Information:** The project employs an Axivity 6-axis IMU sensor (Axivity AX6) to capture 3-axis accelerometer and 3-axis gyroscope readings. The IMU is securely positioned on the rollator, as illustrated in Figure 1.

  ![Rollator Position](images/rollator_position.png)

### Data Collection:
- **Surfaces Investigated:**
  1. Grass
  2. Asphalt with bumps and manhole covers.
  3. Concrete with bumps.

- **Data Generation:**
  - Researchers push the rollator on each surface to generate movements (jitters).
  - The Axivity sensor records acceleration and gyroscope data during these movements.

### Project Goal:
The **primary** objective is to develop machine learning models using Axivity sensor data to accurately determine the surface on which the rollator is being pushed. This recognition is crucial for providing timely AI-based assistance, especially for users navigating varied terrains.

### Repository Structure:
(To be updated later)

### How to Contribute:
1. Clone the repository to your local machine.
    
   git clone https://github.com/your-username/rollator-surface-recognition.git
   
2. Make changes, commit them, and push to your branch.

   git add .
   git commit -m "Description of changes"
   git push origin feature/new-feature

### Dependencies:
(To be updated later)

### Acknowledgments:
- This project is developed by Terrain Detectives for COMP4030: Data Science with Machine Learning at The University of Nottingham.

### References:
- [Axivity AX6](https://axivity.com/product/ax6)
