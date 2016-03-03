# Body_feeling_game
Body Feeling Game System

基于Kinect VS C#实现手势控制俄罗斯方块和手势控制Unity3d人物模型的课题
===================================  
### 游戏的入口
![github](https://github.com/df865017/Body_feeling_game/blob/master/pic/main.jpg "github") 

### 俄罗斯方块界面
![github]( https://github.com/df865017/Body_feeling_game/blob/master/pic/Tetris.jpg "github") 

### 手势控制
![github]( https://github.com/df865017/Body_feeling_game/blob/master/pic/handscontrol.jpg "github") 

### Unity3D人物模型和游戏场景
![github](https://github.com/df865017/Body_feeling_game/blob/master/pic/player.jpg "github") 

### 方法介绍
利用C#编写俄罗斯方块的程序；
通过键盘事件控制俄罗斯方块的相关事件；
开始，暂停，变换，加速，向左，向右。
连接识别Kinect，绘制骨架图像；
导入kinect姿势数据库，识别手势动作；
通过手势识别促发键盘事件，控制俄罗斯方块的游戏。


通过Unity绘制3D场景，加载3D模型；
（2）运用第三人称角色控制器；
（3）加载3D模型动作的方法；
（4）kinect动作识别进行键盘操作；
如果绑定骨架的关节点，而不用模型已有的动作方法，模型与人的动作无法很好的模拟，而是只是对骨架模型的模拟。
键盘控制3D模型 加速前进、跳跃、向右转身，向左转身，向后转身。

综述：
使用Opencv视觉库实现手势控制俄罗斯方块和手势控制Unity3d人物模型的课题，获取Kinect人体骨架图形，实现了6种手势识别和响应操作。
