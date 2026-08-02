# Hi there 👋 I'm Q_Leo

> **苏大 AI · 25级** · 六足机器人 RL · 机械臂优化 · 考研清北

---

### 🧠 About Me

- 🎓 AI major @ Soochow University (class of 2025)
- 🤖 Building **RL-based gait optimization** and **RGB-D perception** for hexapod robots
- 🦾 Competing in **robot arm trajectory optimization**
- 🎯 Target: Tsinghua/Peking University graduate school · Big Tech / Robotics companies
- 🏆 Algorithm competitions · Mathematical modeling · Research publications

---

### 🔭 Current Projects

| Project | Description | Status |
|---------|-------------|--------|
| [**jethexa-rgbd-obstacle-vision**](https://github.com/qleoqq-lang/jethexa-rgbd-obstacle-vision) | Real-robot ROS RGB-D obstacle perception: color contours, registered depth, 3D center, metric size, and a documented output interface | ✅ Validated prototype |
| [**hexapod-rl**](https://github.com/qleoqq-lang/hexapod-rl) | RL-based gait optimization & path planning for hexapod robots using PPO/SAC + MuJoCo | 🚧 In progress |
| [**hexapod-rl-notes**](https://github.com/qleoqq-lang/hexapod-rl-notes) | RL foundations, reproducible experiments, and notes for the hexapod projects | 🚧 In progress |
| [**robot-arm-optimization**](https://github.com/qleoqq-lang/robot-arm-optimization) | Trajectory optimization, inverse kinematics, and control for robotic arms | 🚧 In progress |
| **FiveInARow** | Five-in-a-row game with AI opponent | ✅ Done |

---

### 📌 Featured Build

<a href="https://github.com/qleoqq-lang/jethexa-rgbd-obstacle-vision">
  <img src="https://raw.githubusercontent.com/qleoqq-lang/jethexa-rgbd-obstacle-vision/main/media/2026-08-02_day13_40cm_center.png" alt="JetHexa RGB-D obstacle vision running on the real robot" width="100%">
</a>

**[JetHexa RGB-D Obstacle Vision](https://github.com/qleoqq-lang/jethexa-rgbd-obstacle-vision)** turns RGB and registered depth topics into a documented obstacle result for downstream ROS nodes.

- Completed a 14-day path from ROS topic inspection and OpenCV masks to 3D center, approximate metric size, JSON, and `PoseStamped`
- Repeatedly validated the main `0.30-0.60 m` working range on the real JetHexa robot
- Estimated a `0.18 m` target's long edge at `0.173 m` on average, about `3.9%` error
- Recorded failure boundaries openly: close/far depth gaps, projected-angle limits, and `95.6%` false positives with a large similar-color background

[Run the demo](https://github.com/qleoqq-lang/jethexa-rgbd-obstacle-vision/blob/main/run_notes.md) · [Read the ROS interface](https://github.com/qleoqq-lang/jethexa-rgbd-obstacle-vision/blob/main/docs/obstacle_result_interface.md) · [See the reliability report](https://github.com/qleoqq-lang/jethexa-rgbd-obstacle-vision/blob/main/reports/test_results.md)

---

### 🛠️ Tech Stack

```
Python       ████████████████░░   PyTorch / OpenCV / NumPy / RL
ROS          ███████████░░░░░░░   ROS1 Melodic / Topics / TF / RGB-D
C++          ████████░░░░░░░░░░   Algorithms / Data Structures
Linux        ██████████░░░░░░░░   WSL / Shell / Git
```

---

### 📊 GitHub Stats

[![Q_Leo's GitHub stats](https://github-readme-stats.vercel.app/api?username=qleoqq-lang&show_icons=true&theme=dark&hide_border=true)](https://github.com/qleoqq-lang)

---

### 📫 Let's Connect

[![GitHub](https://img.shields.io/badge/GitHub-qleoqq--lang-181717?style=flat&logo=github)](https://github.com/qleoqq-lang)

---

*⚡ Building robots one gradient step at a time.*
