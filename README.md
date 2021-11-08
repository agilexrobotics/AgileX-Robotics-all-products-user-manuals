# [松灵机器人](https://www.agilex.ai/?lang=zh-cn)产品用户开发指导手册

[中文（用户指南）](https://github.com/agilexrobotics/Agile-Product-UserGuide/blob/master/UserGuider_CN.md)|  [English (User Guide)](https://github.com/agilexrobotics/AgileX-Robotics-all-products-user-manuals/blob/master/UserGuider_EN.md)

松灵机器人成立于2016年,是全球领先的移动机器人底盘制造商和移动机器人系统解决方案提供服务商。公司创始团队和研发团队来自大疆和Mathworks等领军企业和知名科研学府，由李泽湘教授孵化，获得红杉、五源、祥峰亿级投资。

以市场为导向，松灵机器人自主开发的多模态轮式和履带式底盘已实现行业全矩阵覆盖，多款产品获得了CE认证。同时，松灵机器人提供了自动驾驶和平行驾驶解决方案，机器人科研教育套件等配套方案，帮助客户在自动驾驶、机械控制等领域完成实验验证。

凭借领先的研发技术，松灵机器人的产品已覆盖阿里巴巴、华为、本田、中建三局在内的1000+企业级客户,并和中科院、卡耐基梅隆大学、清华大学、纽约大学等全球50多所顶级学府达成深度合作。

Founded in 2016, AgileX Robotics is a leading mobile robot chassis and customized unmanned driving solution provider with a vision to enable all industries to improve productivity and efficiency through robot technology.

AgileX Robotics has developed a full line-up of industry-leading robotics chassis that fully meet all industries requirements, including general UGV, indoor AGV, tracked chassis and many of them obtained CE certification. Back by mature software capabilities, Agilex Robotics also provides customized autonomous driving solutions, including parallel driving solutions, robot R&D kits, mobile manipulator, and autopilot kit to enable customers to accelerate the development and verification of their autonomous driving and robotics projects.

The company’s core teams come from leading companies such as DJI and Mathworks and well-known scientific research institutions. With the in-depth cooperation with over a thousand enterprises including Alibaba, Huawei, Honda, the China Construction Third Engineering Bureau, and over fifty global top universities, AgileX Robotics has deployed more than one thousand applications in a range of industries purposes including autonomous driving, academic research, agriculture management, geographic surveying industries, and more.

<img src="https://github.com/agilexrobotics/agilex.io/blob/master/image/image-20210720181547923.png" alt="image-20210720181547923" style="zoom:200%;" />

------

# 松灵机器人产品发布时间标

| 产品名字             |                           产品图片                           | 发布时间 | 当前维护状态                   |
| -------------------- | :----------------------------------------------------------: | -------- | ------------------------------ |
| SCOUT 1.0            |   <img src="/image/SCOUT%201.0.png" style="zoom: 10%;" />    | 2018.12  | 已经停止生产，技术支持继续维护 |
| HUNTER 1.0           |     <img src="/image/HUNTER1_0.png" style="zoom:30%;" />     | 2019.3   | 已经停止生产，技术支持继续维护 |
| SCOUT mini(越野板)   |   <img src="/image/scout%20mini.png"  style="zoom:10%;" />   | 2019.12  |                                |
| SCOUT mini(麦轮版本) | <img src="/image/scout%20mini_omni.png" style="zoom: 10%;" /> | 2019.12  |                                |
| BUNKER               |      <img src="/image/bunker.png" style="zoom: 10%;" />      |          |                                |
| SCOUT 2.0            |     <img src="/image/scout2.png"  style="zoom: 10%;" />      |          |                                |
| HUNTER 2.0           |      <img src="/image/hunter2.png" style="zoom:25%;" />      |          |                                |
| Ranger MINI          |    <img src="/image/rangermini.png"  style="zoom:25%;" />    |          |                                |
| TRACER               |                                                              |          |                                |
| LIMO                 |                                                              |          |                                |

# 标准底盘产品用户手册列表

* [松灵机器人产品割草车CLEAR_Quick_Start](https://agilexrobotics.gitbook.io/agilex/)
* [松灵机器人产品SCOUT 2.0用户手册](https://agilexrobotics.gitbook.io/scout/)
* [松灵机器人产品HUNTER 2.0用户手册](https://agilexrobotics.gitbook.io/hunter-2-0/6-chan-pin-chi-cun-product-dimensions)
* [松灵机器人产品BUNKER 用户手册](https://agilexrobotics.gitbook.io/bunker/)
* [松灵机器人产品BUNKER PRO用户手册](https://agilexrobotics.gitbook.io/bunker-pro/)
* [松灵机器人产品SCOUT MINI用户手册](https://agilexrobotics.gitbook.io/scout_mini/)
* [松灵机器人产品RANGER MINI用户手册](https://agilexrobotics.gitbook.io/ranger-mini/)
* 松灵机器人产品LIMO用户手册（coming soon）


# 开发套件用户手册

- [松灵机器人产品AutoPoilt 套件用户手册](https://agilexrobotics.gitbook.io/clear-yong-hu-shou-ce/)
- 松灵机器人产品Autoware套件用户手册（Coming soon）

# 仿真支持

- ​	[Gazebo 仿真](https://github.com/agilexrobotics/ugv_gazebo_sim)

  当前支持Gazebo的仿真支持列表

  | Product name     | support status |
  | :--------------- | -------------- |
  | SCOUT 1.0×       | ×              |
  | HUNTER 1.0       | ×              |
  | SCOUT 2.0        | √              |
  | HUNTER 2.0       | √              |
  | SCOUT MINI       | √              |
  | SCOUT MINI(OMNI) | ×              |
  | TRACER           | √              |
  | RANGER MINI      | √              |
  | LIMO             | √              |


# 技术博客汇总

- [松灵机器人CSDN官方博客](https://blog.csdn.net/AgileX)
- [松灵机器人SCOUT的ROS代码架构](https://blog.csdn.net/a850565178/article/details/106427019?spm=1001.2014.3001.5501)
- [松灵机器人 SCOUT的ROS代码架构---CAN通信](https://blog.csdn.net/hltt3838/article/details/108603203?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-2.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-2.control)
- [线控小车底盘松灵SCOUT+激光雷达实现基于cartographer的室内小车导航实现攻略教程](https://blog.csdn.net/l494924841/article/details/109407046?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-17.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-17.control)

# 视频资料/信息汇总

- [松灵机器人官方B站](https://space.bilibili.com/484123810?spm_id_from=333.788.b_765f7570696e666f.1)



# 常见问题的处理

- 遥控器漂移问题的处理（coming soon）
- SDK的开发和测试（coming soon）



# 联系我们

#### 技术咨询与支持

support@agilex.ai

#### 产品咨询

- 邮箱：sales@agilex.ai
- 电话：0769-22892150（周一至周五）
- 手机：19925374409  （周末及节假日）
- 微信：松灵机器人（可扫描以下二维码添加好友）

![image.png](/image/qr_code.png)



#### 市场推广

marketing@agilex.ai

#### 加入我们

hr@agilex.ai

#### 公司地址

东莞公司地址：东莞市松山湖中小企业创业园10栋1楼

深圳公司地址：深圳西丽大学城平山民企科技园1栋A座3层305室