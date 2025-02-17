## 使用本技能提醒请勿截图或直播,会被SE/拂晓组封号,不要在任何场合截图炫耀或宣称使用了任何第三方工具/插件
 由于Splatoon插件是在屏幕上新增一层进行绘制,并没有绘制进游戏本身,所以仅捕捉游戏的OBS看不到此层效果

## 本技能提醒很多触发器逻辑抄写自已发布的普通TTS,会在每一处都标记原始来源
 允许其它人重写/优化并重新发布基于该技能提醒触发器的改进版本

## 本技能提醒可以做什么
 显示本不应显示在地上的技能 (比如雷枪冲锋路径,光玉爆炸半径等)
 ![图片](https://user-images.githubusercontent.com/31427200/170696438-ec78dc68-0bbf-42c9-bf87-d1ce11ae0c4c.png)
 一部分普通TTS功能

## 本技能提醒基于[Triggernometry](https://github.com/paissaheavyindustries/Triggernometry)编写
 **建议使用官方版TRN,整合版内的旧版本可能会无法导入或工作不正常**

## 国服已测试通过 (2022.9.1 / 下载本库的Splatoon.zip并手动安装,或使用SPL的官方Unban工具)
![注意](https://user-images.githubusercontent.com/31427200/187145801-abae17c9-804f-4f36-bb32-382f3b43fe5c.png)

## 本技能提醒需要卫月插件[Splatoon](https://github.com/NightmareXIV/Splatoon)
**没有安装该插件/卫月不可用时请禁用该组触发器,会导致游戏和电脑卡顿**  
在卫月设置中添加以下库后搜索Splatoon进行安装  
**国际服**  
`https://raw.githubusercontent.com/NightmareXIV/MyDalamudPlugins/main/pluginmaster.json`  
**国服**  
`https://raw.githubusercontent.com/NightmareXIV/MyDalamudPlugins/main/cn.json`  
**不要添加错了,否则无法启用插件**  
国服添加插件时会提示这个,按黄框里的按钮  
![QQ截图20220829192153](https://user-images.githubusercontent.com/31427200/187190784-08749c67-d78d-42c4-a055-8aebb901543f.png)  

**建议同时添加DSR Toolbox补全更丰富的提示功能**  
**建议找个视距解锁,不然超出屏幕太多的直线绘制稍有不全**
> 务必启用插件内以下设置
> 
> ![图片](https://user-images.githubusercontent.com/31427200/170856016-206adf2e-54ce-477d-8ca7-0278254efabb.png)   
> 
> 务必取消插件内以下设置   
> 
> ![BF1F9FCAD43E718A0B38FB965B34F61B](https://user-images.githubusercontent.com/31427200/187163001-e637df6a-a8fb-4634-afa5-e123a727348d.png)

## 如果有就功能进行探讨的,欢迎加群838051153
 不负责解决 卫月 / Splatoon / Triggernometry 本身的问题

## 请手动填写玩家名至该触发器
![图片](https://user-images.githubusercontent.com/31427200/170809073-2cfdcd4d-d831-4dae-9f32-e57ffb231d2d.png)

## P1
**锁链站位基于**
> △×□  
> ○  ○  
> □×△  

如需要更改,请前往  

>P1
>
> -索尼按钮
> 
> --我要去哪
> 
> 修改播报位置即可
> 请勿禁用这个触发器,可以禁用其中的语音播报

_该处查找标记的逻辑来自[Discord / Jin❗Vitali#1988](https://discord.com/channels/374517624228544512/399219257302450196/968813549482831882)_

绘制P4.5诱导扇形AOE后放置的地面AOE位置  

## P2一运(雷枪)  
显示冲锋范围  
显示地震范围  
显示托尔丹所在位置(几率不报,但不可能报错)  
明显提示谁点了蓝标  

## P2二运(圣杖)  
光球所在位置标记(觉得比较乱可以关掉光球在哪)  
_配合DSR Toolbox可以提示是否正确背对和龙眼及托尔丹准确位置_  
填写了小队各职业名字时可以语音播报陨石换位(AC固定,同职业换位)  

## P3
显示附在人身上的小抄**务必去绘图功能控制最下面设置小抄大小**  
显示塔预计放在什么位置  
显示塔预计放在了什么位置(可能不准)  
显示诱导的直线AOE  
显示尼德霍格的扇形随机点名AOE  

## P4
语音提示自己什么颜色BUFF  
显示并记录第一组堕天冲到的人  
显示P4.5诱导扇形AOE后放置的地面AOE位置  

## P5一运
显示拉线的人该站的安全点  
显示蓝点名该站的安全点  
显示斧子哥的位置  
显示液体火点了谁(给治疗职业提示用)  
托尔丹的不可躲八方范围  
显示谁点了雷点名  

## P5二运
显示谁点了死宣(意义不大)  
显示冲锋范围  
显示地震范围  

## P6
显示辣翅辣尾  
显示左右翅膀  
显示冰火线站位位置  
显示BUFF与交换时爆炸范围

## P7
显示冰火内外  
显示自己去的塔刷哪了  
显示地火预估 ( 来自Splatoon插件官方 )
