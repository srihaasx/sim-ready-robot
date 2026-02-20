# sim_ready_robot 🤖

Complete ROS2 Humble Gazebo simulation with:
- Custom A* Nav2 planner plugin
- PID velocity controller
- Obstacle avoidance FSM
- SLAM mapping
- Camera node

## Milestones
- [x] Project setup & Docker
- [ ] URDF loads in Gazebo
- [ ] Robot moves with teleop
- [ ] TF tree correct
- [ ] SLAM mapping works
- [ ] Nav2 goal sending
- [ ] A* plugin integrated
- [ ] FSM obstacle avoidance
- [ ] Camera node + demo

## Quick Start
```bash
cd docker && docker compose up -d
docker exec -it sim_robot_dev bash
```
