# 🧠 ROS2 Python Tutorials – Robotics Back-End Series

This repository documents my learning journey through the **ROS2 Python Tutorial Series** by [Robotics Back-End](https://www.youtube.com/c/RoboticsBackEnd). The series offers a comprehensive introduction to ROS2 development using Python, covering everything from nodes and packages to topics, publishers/subscribers, and services.

---

## ✅ Completed Tutorials

| #  | Tutorial Title | Duration |
|----|----------------|----------|
| 1️⃣ | Start Your First ROS2 Node | `10:20` |
| 2️⃣ | Create and Set Up a ROS2 Workspace | `6:11` |
| 3️⃣ | Create a ROS2 Python Package | `10:48` |
| 4️⃣ | Create a ROS2 Node with Python and OOP | `24:11` |
| 5️⃣ | What is a ROS2 Topic? | `10:59` |
| 6️⃣ | Write a ROS2 Publisher with Python | `19:40` |
| 7️⃣ | Write a ROS2 Subscriber with Python | `13:06` |
| 8️⃣ | Create a Closed Loop System with a Publisher and a Subscriber | `14:01` |
| 9️⃣ | What is a ROS2 Service? | `14:21` |
| 🔟 | Write a ROS2 Service Client with Python | `13:38` |

---

## 📌 What I Learned

- ✅ Setting up ROS2 workspace and environment
- ✅ Creating and structuring Python-based ROS2 packages
- ✅ Writing ROS2 Nodes with Object-Oriented Programming
- ✅ Understanding and implementing Topics in ROS2
- ✅ Building Publisher and Subscriber nodes in Python
- ✅ Creating closed-loop communication systems
- ✅ Understanding and implementing ROS2 Services

---

## 📂 Repository Structure

```

├── my_robot_controller/
│   ├── __init__.py
│   ├── draw_circle.py
│   ├── my_first_node.py
│   ├── pose_subscriber.py
│   └── turtle_controller.py
│
├── resource/
│   └── my_robot_controller/
│
├── test/
│   ├── test_copyright.py
│   ├── test_flake8.py
│   └── test_pep257.py
│
├── package.xml
├── setup.py
├── setup.cfg
└── .vscode/
│
└── README.md
```


> Each folder contains code following the tutorials and additional notes where applicable.

---

## 🚀 How to Run

```bash
# Source ROS2 environment
source /opt/ros/humble/setup.bash

# Navigate to workspace
cd ~/ros2-python-tutorials/workspace/

# Build the workspace
colcon build

# Source the workspace
source install/setup.bash

# Run a node
ros2 run my_package_name my_node_name
```

---

## 🎓 Credits

Big thanks to **Robotics Back-End** for this excellent tutorial series:
👉 [YouTube Channel](https://www.youtube.com/c/RoboticsBackEnd)

---

## 📫 Contact

Feel free to reach out for collaboration or ROS2 discussions!

**Akindu Kalhan**  
📧 akinduk619@gmail.com 
🌐 [LinkedIn](https://www.linkedin.com/in/akindu-kalhan/) • [GitHub](https://github.com/akindu-k)

---

