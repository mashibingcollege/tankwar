## 项目演示

![tank1](https://github.com/mashibingcollege/tankwar/blob/main/Tank2019V2/src/readmejpg/tank1.png)


![tank2](https://github.com/mashibingcollege/tankwar/blob/main/Tank2019V2/src/readmejpg/tank2.png)

小福利：小编准备了1700+页的面试题集锦，关注公众号“程序员二哥”，发送“666”领取

## 关键技术

java基础知识栈

融汇23种设计模式实战演练

深入了解netty底层原理及灵活应用

项目融合了java基础知识栈、将设计模式应用在实战项目中，netty网络通信，实现了玩家间的交互



## 项目介绍

坦克大战联机对战游戏是马老师耗时数月精心打造的经典java项目，学习人次量达百万级别，配套完整视频19课时，项目通过手把手教学，经历一行一行代码的开发过程，深入浅出的让你深刻理解和运用JavaSE，DesignPatterns , TCP/IP, 多线程, NIO，netty等基础知识。真正做到理解实战项目的开发过程。



## 代码模块介绍

```xml
Tank2019V2                                父项目
--lib   	                                存放jar包
--out                                     反编译包
--src                                     源码包
	--audio                                 音频
	--com                                   源码
		--chainofresponsibility               实体间碰撞包
			--BulletTankCollider                子弹和坦克碰撞
			--BulletWallCollider                子弹和墙碰撞
			--Collider                          碰撞抽象类
			--ColliderChain                     碰撞链
			--TankTankCollider                  坦克和塔克碰撞
			--TankWallCollider                  坦克和墙碰撞
		--net                                 网络包
			--BulletNewMsg                      子弹消息类
			--Client                            客户端
			--Msg                               消息抽象类
			--MsgDecoder                        消息解码
			--MsgEncoder                        消息编码
			--MsgType                           消息枚举类型
			--Server                            服务端
			--ServerFrame                       服务端窗口
			--TankDieMsg                        坦克死亡消息
			--TankJoinMsg                       坦克加入消息
			--TankMoveOrDirChangeMsg            坦克移动或方向改变
			--TankStopMsg                       坦克停止消息
		--strategy                            策略包
			--DefaultFireStrategy               默认开火策略
			--FireStrategy                      开火策略
			--FourDirFireStrategy               四个方向开火策略
			--LeftRightFireStrategy             左右方开火策略
			--LeftUpFireStrategy                左上方开火策略
		--AbstractGameObject                  抽象游戏对象类
		--Audio                               音频类
		--Bullet                              子弹类
		--Dir                                 方向类
		--Explode                             爆炸类
		--GameModel                           游戏模型类
		--Group                               分组类
		--ImageUtil                           图片工具类
		--Main                                主方法类
		--Player                              玩家类
		--PropertyMgr                         属性管理类
		--ResourceMgr                         资源管理类
		--Tank                                坦克类
		--TankFrame                           坦克窗口类
		--Wall                                墙类
	--images                                图片
--test                                    测试包
```



## 项目运行

启动ServerFrame类，是网络版的服务端

启动main主启动类，是网络版的客户端，可设置Allow parallel run开启多个客户端坦克做对战演示



## 公众号

如果大家想要实时关注我更新的文章以及分享的干货的话，可以关注我的公众号“程序员二哥”。

由马士兵教育面试专家专门为学生面试编撰的《BAT面试突击》手册，公众号后台回复 **"BAT面试"** 即可领取！

![gongzhaonghao](https://github.com/mashibingcollege/tankwar/blob/main/Tank2019V2/src/readmejpg/gongzhaonghao.png)

