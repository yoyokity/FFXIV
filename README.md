# FFXIV （ACT)触发器工具  说明书

 - [自动屏幕录制工具](#自动屏幕录制工具)
 - [游戏私聊QQ提醒](#游戏私聊QQ提醒)




----------


## 自动屏幕录制工具

> 注：
> 
>  - 工具基于Triggernometry高级触发器1.1.3.0，请从这里导入。
> 
>        
>  - 录屏软件自己准备好，本工具只是对录屏软件的快捷键做自动按下的操作。推荐使用N卡驱动自带的录屏功能。

  
  

 - **使用效果：**
每把战斗（从开怪倒数到团灭）自动开始录屏以及关闭，自动实现一次战斗一个视频文件，不需要手动控制，有效避免了“忘记录了”、“一次录太长回放时候不好定位”等不必要的麻烦，解放双手，专注打本，~~重拳出警~~！


 

 - **使用方法：**

 

     1. 导入Triggernometry高级触发器后，双击“录制”触发器。
![enter description here](https://i.loli.net/2020/01/24/vZejd17X8PEnAS9.png)
     2. 再双击这个动作，
 
   ![enter description here](https://i.loli.net/2020/01/24/B5OdxwgqlFAr6yY.png)
 
   3. 修改你自己电脑的录屏快捷键。

   ![enter description here](https://i.loli.net/2020/01/24/1aEUj5oZngyVxQu.png)

   A-Z,0-9就正常输入进去，如果是其他键像F1、F4这样的，记得加上花括号{}哦，如：{F1}
    如果是组合键，加上前缀就行。
    
   shift —— + 
    
   ctrl      —— ^ 
    
   alt       —— %
    
   比如alt+F9就输入“%{F9}”。
   
   [更多详细用法可以点我去微软官方查看](https://docs.microsoft.com/en-us/dotnet/api/system.windows.forms.sendkeys.send?redirectedfrom=MSDN&view=netframework-4.8#System_Windows_Forms_SendKeys_Send_System_String_)

> #### **高级用法：**
>
>    如果你觉得每次进想要录屏的副本都要手动开关触发器太麻烦，这边有更懒人的方案。
> - 勾上“仅限当前副本内开关”后，录屏触发器会默认关闭，每次你进入了你想要录屏的副本后，只需要在聊天框里输入“**启用录像**”或者“**video on**”这两个指令，工具就会在当前副本里自动录下你每一把的战斗。并且当你退出副本后，触发器随即就会关闭。


----------
## 游戏私聊QQ提醒

> 注：
> 
>  - 工具基于Triggernometry高级触发器1.1.3.0，请从这里导入。

 - **使用效果：**

    当你挂机离开时，或者挂** 时，有人在游戏内私聊你，加载这个触发器就可以通过QQ机器人向你发送告知信息比如：![enter description here](https://i.loli.net/2020/02/17/xNfvyZ3eRgLzHAK.png)


 
 
 - **使用方法：**
   
   首先，你QQ需要一个獭獭机器人好友位（必须是獭爹的獭獭机器人，不是塔塔露），自己搞一个机器人或者去别的群白嫖一个，加了好友即可，临时会话是没有用的哦！
   
   有了机器人好友之后，对它输入token信息（不超过16个字符）作为标识码：“/bot token (你随便取的token码)”。

   有了标识码以后进入ACT内打开“设置”触发器![enter description here](https://i.loli.net/2020/02/17/qGWAacFB1hHJvSD.png)，

   依次设置好“你的qq”；“机器人qq”；“token”：![enter description here](https://i.loli.net/2020/02/17/DEFLC74UuKHoifS.png)


以上就是使用方法了，注意：因为獭獭机器人不能快速连续发消息，因此触发器设置了每次给你发消息的间隔是最少5秒，不过放心，不会漏掉私聊消息得啦~~
