---
layout: default
title: Skills
permalink: /skills/
---

## 🧠 Technical Skills

### Python (Proficiency: 8/10)
Extensive experience using Python across both undergraduate and postgraduate projects.  
- Built a face recognition system, blood cell classification, and a data mining competition solution.  
- Developed a deep learning-based UAV image matching system for the undergraduate thesis using Geodesc.  
- Currently applying Python for object detection and UAV attitude control in postgraduate research.  
Python is my primary development language, particularly for robotics control and computer vision.

### ROS2 (Proficiency: 6/10)
Hands-on experience building a complete robotic system for autonomous navigation and target grasping.  
- Designed a full ROS2 pipeline integrating sensor input, perception, and motion planning.  
- Implemented topic-based communication between system nodes for real-time robot coordination.

### PyTorch (Proficiency: 5/10)
Used PyTorch to train the Geodesc deep feature descriptor during the undergraduate thesis.  
- Trained on the GL3D dataset and compared the descriptor's matching performance against SIFT.

### OpenCV (Proficiency: 6/10)
- Applied OpenCV in real-time face recognition using the LBPH algorithm.  
- Used OpenCV for object detection from depth cameras, feature extraction, and visualization.

### Gazebo / RViz (Proficiency: 4/10)
- Simulated robot navigation and SLAM in Gazebo environments.  
- Visualized mapping and sensor data using RViz.

### C++ (Proficiency: 6/10)
- Built a student score management system with C++ during undergraduate studies.  
- Familiar with object-oriented programming and foundational data structures.  
- Used alongside Python for robotics, but Python is currently the main development language.

### CAD Tools (SolidWorks / Fusion 360) (Proficiency: 3/10)
- Modeled sensor brackets and robot components using SolidWorks and Fusion 360.  
- Designed printable mechanical parts for robotic integration.

---

## 📊 Skill Proficiency Radar Chart

<div>
  <canvas id="skillsRadarChart" width="400" height="400"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  const ctx = document.getElementById('skillsRadarChart').getContext('2d');
  const radarChart = new Chart(ctx, {
    type: 'radar',
    data: {
      labels: ['Python', 'ROS2', 'PyTorch', 'OpenCV', 'Gazebo/RViz', 'C++', 'CAD Tools'],
      datasets: [{
        label: 'Skill Level (out of 10)',
        data: [8, 6, 5, 6, 4, 6, 3],
        fill: true,
        borderColor: 'rgba(54, 162, 235, 0.7)',
        backgroundColor: 'rgba(54, 162, 235, 0.2)',
        pointBackgroundColor: 'rgba(54, 162, 235, 1)',
        pointBorderColor: '#fff',
        pointHoverBackgroundColor: '#fff',
        pointHoverBorderColor: 'rgba(54, 162, 235, 1)'
      }]
    },
    options: {
      scales: {
        r: {
          suggestedMin: 0,
          suggestedMax: 10
        }
      }
    }
  });
</script>
