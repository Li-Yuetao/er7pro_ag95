# ER7PRO+AG95

#### 注意：
- 启动机械臂时候`er7pro_driver.launch`需要在`hardware_startup.launch`启动后运行
- 在`er7pro_driver.launch`文件中修改`local_ip`和`robot_ip`
启动顺序：
1. `roslaunch er7pro_ag95_startup hardware_startup.launch`
2. `roslaunch er7pro_ag95_startup er7pro_driver.launch`
3. `roslaunch er7pro_ag95_startup software_startup.launch`