# rl_isaac_human_dog
2024.9.20

## 1. isaac-lab学习
### 初始化
官方文档+范佬的中文文档

https://isaac-sim.github.io/IsaacLab/source/setup/installation/index.html

```
conda activate isaaclab
cd /home/hhz/UCAS/2024/IsaacLab

```

## 2. robot-lab
范佬

https://docs.robotsfan.com/isaaclab/



### 初始化
```
conda activate isaaclab
cd /home/hhz/UCAS/2024/robot_lab
```

## 3. 飞书项目-机械狗-不规则路面行走   竞赛（5k）
### 训练
```
conda activate legged_robot
cd /home/hhz/UCAS/2024/dog_isaac/competition_v1-2/competition/legged_gym/legged_gym/scripts

python train.py --task=go2 --num_envs=2048 --headless

```
### 演示
```
python play.py --task=go2 --load_run=/home/hhz/UCAS/2024/dog_isaac/competition_v1-2/competition/legged_gym/logs/rough_go2/Aug20_20-xxxx --resume --checkpoint=100 --num_envs=32

```
