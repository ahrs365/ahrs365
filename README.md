<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=12,20,24&height=160&section=header&text=Gao&fontSize=56&fontColor=ffffff&fontAlignY=40&desc=Embodied%20AI%20%C2%B7%20VLN%2FVLA%20%C2%B7%20Motion%20Planning&descSize=18&descAlignY=70" alt="header" />

</div>

---

## 关于我

我专注于把大模型 / 视觉语言模型与机器人导航、传统规划与最优控制结合起来，让具身智能从论文 Demo 走向可运行、可复现的工程系统。

- 在做：低成本 VLN/VLA 机器人平台（云边端架构 + ESP32 真机部署）
- 擅长：iLQR / AL-iLQR / MPC / DWA / B-spline 等轨迹优化与运动规划算法的 C++ 工程实现
- 关注：如何让 VLA / VLN 前沿模型真正落到可控、可调、可部署的机器人系统里
- 求职方向：具身智能 / 机器人导航 / 自动驾驶规划控制 / 多模态 AI

---

## 代表项目

### AHBot-VLA — 低成本视觉语言导航机器人平台

把 VLN/VLA 的研究能力跑在真实差速底盘上，覆盖感知 → 推理 → 控制全链路。

[![Repo](https://img.shields.io/badge/GitHub-ahbot--vla-181717?style=flat-square&logo=github)](https://github.com/ahrs365/ahbot-vla)
![Stars](https://img.shields.io/github/stars/ahrs365/ahbot-vla?style=flat-square&label=Stars)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)

- OpenClaw 作为高层 Agent / 大脑，OmniVLA 用于视觉语言导航实验
- 手机摄像头 + 传感器作为前端感知，云边端推理架构串联图像、状态与任务指令
- ESP32 差速底盘完成底层运动控制

体现能力：具身智能系统集成 / VLN/VLA 实践 / 机器人软硬件联调 / 云边端架构设计

---

### AL-iLQR Starter — 增广拉格朗日 iLQR 时空联合规划

从零实现的约束最优控制求解器，面向自动驾驶与移动机器人轨迹优化。

[![Repo](https://img.shields.io/badge/GitHub-al--ilqr--starter-181717?style=flat-square&logo=github)](https://github.com/my-al-ilqr/al-ilqr-starter)
![Stars](https://img.shields.io/github/stars/my-al-ilqr/al-ilqr-starter?style=flat-square&label=Stars)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Eigen](https://img.shields.io/badge/Eigen-3F51B5?style=flat-square)

- 完整实现 Augmented Lagrangian iLQR 求解器
- 前向 rollout / 反向 Riccati 递推 / 正则化 / 线搜索 / 约束惩罚更新
- 面向自动驾驶 / 机器人场景的时空联合轨迹规划
- 算法原理推导 + 工程实现 双重打通

体现能力：轨迹优化 / 最优控制 / iLQR / MPC / C++ 算法工程化

---

### Planner Backend — 面向 Web 仿真的局部规划算法后端

集成 DWA / DDR-OPT / TMPC / B-spline 的 C++ 规划后端，与 Web 仿真前端联动。

[![Repo](https://img.shields.io/badge/GitHub-planner__backend-181717?style=flat-square&logo=github)](https://github.com/ahrs365/planner_backend)
![Stars](https://img.shields.io/github/stars/ahrs365/planner_backend?style=flat-square&label=Stars)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socket.io&logoColor=white)

- DWA / DDR-OPT / TMPC / B-spline 多种局部规划器统一架构
- C++ WebSocket 服务，与前端仿真系统实时联动
- 算法对比、参数调优、可视化一体化

体现能力：传统规划算法 / 局部路径规划 / C++ 后端服务 / 仿真系统集成

---

## 技术栈

**具身智能与机器人**

![VLA](https://img.shields.io/badge/VLA-FF6F61?style=for-the-badge)
![VLN](https://img.shields.io/badge/VLN-FF8C42?style=for-the-badge)
![Embodied AI](https://img.shields.io/badge/Embodied%20AI-9D4EDD?style=for-the-badge)
![ROS](https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

**运动规划与控制**

![iLQR](https://img.shields.io/badge/iLQR-1F6FEB?style=for-the-badge)
![AL--iLQR](https://img.shields.io/badge/AL--iLQR-2D9CDB?style=for-the-badge)
![MPC](https://img.shields.io/badge/MPC-0EA5E9?style=for-the-badge)
![DWA](https://img.shields.io/badge/DWA-14B8A6?style=for-the-badge)
![B--spline](https://img.shields.io/badge/B--spline-10B981?style=for-the-badge)
![Trajectory Opt](https://img.shields.io/badge/Trajectory%20Optimization-22C55E?style=for-the-badge)

**编程与工程**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## GitHub 数据

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ahrs365&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub Stats" />

</div>

---

## 我希望加入的团队

正在做以下方向的团队，我都很感兴趣：

- 具身智能机器人 / 机器人基础模型
- VLN / VLA / Robot Foundation Model
- 自动驾驶规划控制 / 局部与时空联合规划
- 移动机器人系统工程 / 云边端架构
- 多模态 AI 与机器人结合

我尤其关注：如何把前沿的 VLA / VLN 模型，真正部署到可运行的机器人系统中，并与传统规划、控制、感知和工程系统结合。

---

## 联系方式

| 渠道 | 链接 |
|---|---|
| GitHub | [@ahrs365](https://github.com/ahrs365) |
| 博客 | [gl-robotics.com](https://www.gl-robotics.com) |
| Email | [ahrs365@outlook.com](mailto:ahrs365@outlook.com) |

---

<details>
<summary><b>English Version</b></summary>

<br>

### About me

I focus on bridging Large / Vision-Language Models with robot navigation, classical planning and optimal control, turning embodied-AI papers and demos into runnable, reproducible engineering systems.

- Building: a low-cost VLN/VLA robot platform (cloud–edge–device + ESP32 deployment)
- Skilled in: iLQR / AL-iLQR / MPC / DWA / B-spline trajectory optimization and motion planning in C++
- Interested in: how to land state-of-the-art VLA / VLN models into controllable, tunable, deployable robot systems
- Looking for roles in: Embodied AI / Robot Navigation / Autonomous Driving Planning and Control / Multimodal AI

### Featured Projects

**AHBot-VLA — Low-cost VLN robot platform.** End-to-end stack: OpenClaw (high-level agent) + OmniVLA (VLN), phone-camera perception, cloud–edge–device inference and ESP32 differential-drive control. Skills: embodied-AI system integration, VLN/VLA practice, HW/SW co-debugging, cloud-edge architecture. [Repo](https://github.com/ahrs365/ahbot-vla)

**AL-iLQR Starter — Spatio-temporal planning via Augmented Lagrangian iLQR.** A from-scratch constrained optimal-control solver for AV / mobile-robot trajectory optimization, covering rollout, Riccati backward pass, regularization, line search and AL multiplier updates. Skills: trajectory optimization, optimal control, iLQR/MPC, production-grade C++. [Repo](https://github.com/my-al-ilqr/al-ilqr-starter)

**Planner Backend — C++ local-planning service for web simulation.** Unified backend integrating DWA / DDR-OPT / TMPC / B-spline planners, exposed via WebSocket for a web simulator. Skills: classical planning algorithms, local path planning, C++ backend, simulation integration. [Repo](https://github.com/ahrs365/planner_backend)

### Looking for teams in

Embodied AI · VLN / VLA / Robot Foundation Model · Autonomous-Driving Planning and Control · Mobile-robot systems engineering · Multimodal AI for robotics.

### Contact

GitHub [@ahrs365](https://github.com/ahrs365) · Blog [gl-robotics.com](https://www.gl-robotics.com) · Email [ahrs365@outlook.com](mailto:ahrs365@outlook.com)

</details>
