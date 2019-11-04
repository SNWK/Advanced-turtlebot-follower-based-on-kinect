# Advanced-turtlebot-follower-based-on-kinect
Advanced turtlebot follower based on Kinect and Openni 
基于kinect骨架追踪的跟随机器人，实现手势控制骨骼
### Finished
1. 更改openni_tracker, 增加publisher可以publish追踪状态和追踪对象
2. follower主程序实现：
  - 追踪功能
  - 缓慢刹车不卡顿
  - 右手抬起停车
  - 右肩上方拍手，定点泊车，自动行驶至拍手位置
  - 失去追踪缓慢旋转直至重新追踪成功
  - 使用kobuki声音包，实现声音提醒
