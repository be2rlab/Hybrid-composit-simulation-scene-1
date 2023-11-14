# Репозиторий для моделирования работы робота Kuka iiwa с камерой Intel Realsense D435 и лидаром Robosense

## Установка

### Пререквизиты
1. [Ubuntu 20.04](https://releases.ubuntu.com/focal/)
2. [ROS Noetic Ninjemys](http://wiki.ros.org/noetic)
3. [Gazebo](https://gazebosim.org/home)

## Как установить?

В рабочее пространство ROS скачать репозитории для симуляции в Gazebo сенсоров:
1. [Intel Realsense d435](https://github.com/issaiass/realsense2_description)
2. [Realsense-Gazebo plugin](https://github.com/pal-robotics/realsense_gazebo_plugin)
3. [Robosense lidar](https://github.com/tomlogan501/robosense_simulator)

Скачать данный репозиторий в рабочее пространство ROS.

Собрать пакеты, используя catkin_make или catkin build.

Запустить:

```bash
roslaunch iiwa_gazebo iiwa_gazebo.launch 
```
