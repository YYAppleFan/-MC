# 风音MC

该项目包含风音服务器的开发以及服务器的搭建教程。

该项目的Minecraft服务器暂未开放，正在构建中。预计最大承载量20人，带有纯净生存、PVP、PVE等玩法。服务器内测时问OP要整合包。

（服主第一次搞服务器，啥都不知道，还要中考，ヾ(๑╹◡╹)ﾉ"）

该项目所包含的教程包括基于CraftBukkit、SpigotMC以及Sponge的服务器搭建方法、文件下载。

# 服务器的详细信息(正式发布后更新细节)
服务器所使用的Minecraft版本：1.8.9 (如果之后有时间，开发个1.13的)；

启动器：Hello! Minecraft Launcher (https://github.com/huanghongxun/HMCL)

API:自带Forge API 11.15.1.1890 (http://files.minecraftforge.net/)
和 Optifine API HD U I3 (https://www.optifine.net/home)

服务端：SpongeForge 4.2.0-BETA-1653 (https://spongepowered.org)

模组:[1.8.9] 按键显示.jar

[1.8.9] 方块信息.jar

[1.8.9] 简洁血条.jar

[1.8.9] 龙翼显示.jar

[1.8.9] 输入修复.jar

[1.8.9] 药装显示.jar

[1.8.9] 坐标显示.jar

材质包:药儿、条码、灰机PVP材质包

光影包：CONTINUUM 光影效果包

KUDA 光影效果包

SONIC ETHER’S （SEUS） 光影效果包

SILDURS 光影效果包

SM 光影效果包

MRMEEPZ 光影效果包

CYBOX 光影效果包

# 服务器搭建教程
如果你尚不清楚Minecraft的基本操作，整合包中包含一个地图，以供学习（稍后发布）

如果你已经了解基本操作，就可以着手建立服务器了。要求的最低配置：2GB RAM,10M光纤（可带动20人加入，不可同时运行其他程序，否则FPS会大大降低）。

要开启服务器，必须下载一个服务端文件来启动和管理服务器。MOJANG官方提供了最新MC版本的服务端（“纯净服”）及启动方法(https://minecraft.net/zh-hans/download/server)，直接下载：(https://s3.amazonaws.com/Minecraft.Download/versions/1.8.9/minecraft_server.1.8.9.jar)，如想下载对应自己版本的服务端，请将上方网址中的“1.8.9”改为自己的版本再下载。

【注意：服务端只会将服务器存档公布到网络上，并不能启动客户端进入游戏】

就如Mod对Minecraft。服务器也有“Mod”——插件。Mod需要Forge加载，插件也需要由服务端特定的来加载。在1.8版本以下，CraftBukkit（水桶服，下称CB），SpigotMC（水桶服衍生，下称SG），在1.8版本以上，以SpongeForge（海绵服）为主。

首先介绍一下CB和SG。CB是第一个带插件的服务端，SG是衍生版本。后因CB因未公开所有代码违反了其加入的DMCA开源协议，致其官方下载点被移除，SG也受牵连。CB和SG通过另一种方法发布新版本——搭建工具（BuildTools.jar）,类似一个在线安装包，可在这里下载：(https://hub.spigotmc.org/jenkins/job/BuildTools/)。要使用这个搭建工具，需要Java(www.java.com)和Git(http://msysgit.github.io/)。安装完之后选择一个放置服务器文件的文件夹，将搭建工具放到该文件夹里，然后右键选择“Git Bash Here”,输入以下代码：java -jar <将搭建工具.jar拖动至该窗口> --rev <MC版本>，等待其下载完成。

【注意：由于CB和SG都需要纯净服才能运行且通过Bash下载太慢，建议提前在服务器文件夹中准备好MOJANG官方提供的服务端，否则极大几率会失败】

最后在该文件夹新建一个TXT文档，输入

@ECHO OFF
java -Xms1g -Xmx1g -jar <此处换成你下载到的文件的文件名>.jar
pause
# 问答
Q1:什么时候开服？

A1：应该在暑假，服主得把中考搞好。

Q2：开服后如何进入服务器？

A2：开服后，本页面将更新整合包下载地址。

Q3：我有建议应在哪里反馈？

A3：点击在本项目上方的“Issues”，再点击绿色的“New Issues”进行反馈即可。

# 鸣谢
HMCL作者及主要贡献者：huanghongxun

Forge的开发者们

Optifine的开发者们

SpongeForge的开发者们

所有模组的开发者们

触手平台主播：药儿哟、萌萌哒条码、天才小灰机

光影包的作者们
