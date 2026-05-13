# ROS2 Navigation Project: Global A* Planner + Pure Pursuit Controller

[![ROS2 Humble](https://img.shields.io/badge/ROS2-Humble-blue)](https://docs.ros.org/en/humble/)
[![Ubuntu 22.04](https://img.shields.io/badge/Ubuntu-22.04-orange)](https://ubuntu.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Проект** демонстрирует автономную навигацию мобильного робота (TurtleBot3) в симуляторе Gazebo с использованием ROS2 Humble. Реализовано:

- построение карты (`/map`) в реальном времени на основе данных лидара (`/scan`);
- глобальное планирование пути с помощью алгоритма A*;
- локальное управление методом Pure Pursuit;
- визуализация в RViz, включая установку цели через `2D Goal Pose`.

## 📌 Репозиторий

Склонируйте проект:

```bash
git clone https://github.com/Yazan-pyth/ros2_navigation_project.git
