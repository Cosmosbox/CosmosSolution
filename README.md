CosmosSolution
==============

CosmosSolution 是一套Cosmosbox游戏工作室使用的开发解决方案.


游戏客户端:
--------------
* Unity3D游戏引擎
* [CosmosEngine开发框架](https://github.com/Cosmosbox/CosmosEngine)
* CosmosPro (CosmosEngine的再一层内部常用封装)
* CosmosLevelEditor (内部使用的关卡编辑器，针对特定项目）


游戏服务端：
-----------------
* Pomelo - NodeJS分布式框架
* Pomelo Admin - 针对服务器框架的管理平台定制
* Pomelo Robot - 机器人及压力测试


团队桌面小工具
---------------------
* [KKDaemon - Windows托盘小工具，常用于Excel表编译](https://github.com/mr-kelly/KKDaemon)

版本管理
---------------------
* 使用SVN进行版本管理
* 使用Python调用SVN进行差异化更新相关


团队服务器
---------------
一台物理机，一个一级虚拟机，一个二级虚拟机：

* Mac Mini，
* Mac上使用Parrallels Desktop虚拟化的Windows
* 虚拟化的Windows里的二级虚拟机Vagrant


自动构建（持续集成）工具
--------------------
* Hudson (Java)

自动化
------------------
* 大量的Python、BAT批处理进行自动化工作
