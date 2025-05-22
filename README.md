## 🚗 Swayatri: Deep Learning-Powered Autonomous Driving System

**Swayatri** is a collection of deep learning and computer vision-based modules designed to simulate and build core functionalities of an autonomous driving system. The project focuses on providing a reliable and intelligent framework for autonomous vehicle navigation through perception, planning, and control.

### 🔍 Objectives

The main goal of **Swayatri** is to explore and implement real-world autonomous vehicle concepts using modern AI and deep learning techniques. This system is broken into modular projects, each addressing a specific challenge faced by self-driving cars.

---

### 🛠️ Core Modules

1. **Lane Line Detection**

   * Detects simple lane lines from road images or video feed using classical computer vision techniques (Canny edge detection, Hough Transform).
   * Helps the vehicle understand the correct path and stay within the designated driving lanes.

2. **Advanced Lane Finding**

   * Uses deep learning and advanced CV to identify:

     * Curved lane lines
     * Lane boundary types (dashed, solid, etc.)
     * Other vehicles and obstacles
   * Involves semantic segmentation and object detection models.

3. **Traffic Sign Classification**

   * Uses a Convolutional Neural Network (CNN) to classify road signs (stop, speed limit, yield, etc.).
   * Trained on datasets like German Traffic Sign Recognition Benchmark (GTSRB).

4. **Behavioral Cloning**

   * Mimics human driving behavior using a neural network trained on driver video footage and corresponding steering/brake inputs.
   * Predicts steering angle and brake/throttle values from raw camera input.

5. **Extended Kalman Filters**

   * Implements EKFs to fuse noisy sensor data (like GPS and IMU) and track the vehicle's position more accurately.
   * Used for state estimation in a dynamic environment.

---

### 🚀 Advanced Modules

1. **Localization using the Kidnapped Vehicle Problem**

   * Solves the problem of determining the vehicle’s position on a map even after starting in an unknown location.
   * Uses probabilistic methods such as Particle Filters or Monte Carlo Localization (MCL).

2. **Path Planning**

   * Determines the optimal trajectory from the vehicle’s current location to a target location while avoiding obstacles.
   * Implements techniques like A\*, Dijkstra, and spline-based trajectory generation.

3. **PID Control**

   * Implements Proportional-Integral-Derivative (PID) controllers for:

     * Steering correction
     * Speed control
   * Ensures smooth and stable driving by reducing error between desired and actual vehicle states.

---

### 🧠 Technologies Used

* Python
* OpenCV
* TensorFlow / PyTorch
* NumPy, SciPy
* Matplotlib & Seaborn (for visualization)
* ROS (optional for real-time robotics simulation)
* CARLA / Udacity Simulator (for testing environments)

---

### 📦 Future Plans

* Integration with simulators like CARLA for end-to-end testing.
* Real-time deployment on edge devices (e.g., Jetson Nano or Raspberry Pi with cameras).
* Incorporation of Reinforcement Learning for decision-making modules.

---

