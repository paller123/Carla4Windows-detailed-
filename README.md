# Carla4Windows-detailed-
踩坑一整天终于完美编译运行，为了防止小伙伴们继续踩坑，将分为几个步骤介绍我的安装过程，照着做应该不会出问题。
________________________________________________________________________________________________________
一、确定编译环境
(`Cmake-3.15.0-win64x64.msi`
`make-3.81.exe`
`python-3.72-amd64.exe`
`vs2017(version=15.9)`
`git 2.27.0`
`UE4.24.3`)  
建议各环境版本严格固定，不然不知道可能会报什么错！
__________________________________________________________________________________________________________
二、环境配置  
a：python，Cmake安装的时候记得勾选添加环境变量  
![image](https://github.com/paller123/Carla4Windows-detailed-/blob/master/image/3ce7250e6534b9e796c79c80053305d.png)  
![image](https://github.com/paller123/Carla4Windows-detailed-/blob/master/image/f8c48b0d59cf9562cb89d3ebe79aca8.png)  
b：其他则需要手动添加环境变量  
![image](https://github.com/paller123/Carla4Windows-detailed-/blob/master/image/a21575a04a00e5e4b78334536bdbca4.png)  
c：vs2017安装勾选如图所示  
![image](https://github.com/paller123/Carla4Windows-detailed-/blob/master/image/4f445fe3d34ba0d3c0f28442c0a54b1.png)
![image](https://github.com/paller123/Carla4Windows-detailed-/blob/master/image/7d78fb1d49b897d17766a90e5ce38aa.png)
d：UE4添加环境变量  
![image](https://github.com/paller123/Carla4Windows-detailed-/blob/master/image/31e62186ca9e7e38c0364f7fd7d9e23.png)
____________________________________________________________________________________________________________
三、Carla下载(需全程vpn)  
a：git clone https://github.com/carla-simulator/carla.git(不要用码云！！直接挂vpn下)  
b：通过（适用于 VS 2017 的 x64 本机工具命令提示）进行编译，一定不要cmd或者其他command  
![image](https://github.com/paller123/Carla4Windows-detailed-/blob/master/image/c24d241ee8e4bca9507ab2f3975ffac.png)
c：cd carla  
d:make launch  
e：make PythonAPI  
_____________________________________________________________________________________________________________
bingo！  


_______________________________________________________________________________________________________
附部分安装包百度云链接：链接：https://pan.baidu.com/s/17K3HNbmHmNaqVjQmGJ4C6g 提取码：mp85 
