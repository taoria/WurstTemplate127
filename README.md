# WurstTemplate127
WurstTemplate for 1.27 with dzapi

just simply download it and update with your wurstsetup program.

start your journey of wurst with 1.27 then.

note that a specified warcraft3 may be required for DZAPI environment.(which could be downloaded from the Netease platform ,I think) 

the template itself don't provide any  plugin . it's just a  modified version of hello world project for an easy start.

if your warcraft are not able to load YDWE env automatically.maybe you just need use YDWEConfig.exe to start the warcraft manually after build 

and the templates provided two fast ways to launch YDWEConfig.exe

1. check the run.bat
2. click the generated map and run the task. 
```
        run map with YDWEConfig
```

you have to config the path of the YDWEConfig yourself in both ways.

letter version may use a better task.json to launch.
# Wurst127

下载然后使用WurstSetup程序更新一下即可.

可能需要特殊版本的魔兽来启动DZAPI.

如果你的魔兽并不能自动的装载YDWE的环境,也许你需要在构建项目完毕后,使用YDWEConfig.exe来手动的启动地图测试.

这里给出了两个快捷的方法.

1. 检查一下run.bat文件,修改YDWE的文件路径和build的文件名即可

2. 或者在vs的工作界面中选中生成的w3x文件,按shift+alt+F10运行任务.

```
        run map with YDWEConfig
```

你依然要在task.json中配置ydweconfig.exe的路径.也就是command命令.