# CoppeliaSim/VREP(V-Eep)

[toc]

## 安装

### Linux(ROS, Python等接口)

1. [官网下载Edu版本](https://coppeliarobotics.com/downloads)

2. 解压

3. 进入解压文件夹终端，键入

   ```bash
   ./coppeliaSim.sh
   ```

### Windows(Ｍatlab, Python等接口)

1. [官网下载Edu版本](https://coppeliarobotics.com/downloads)
2. 安装
   - Installer 安装默认路径 或者自定义（注意记住安装路径）
3. 快捷方式

## 实验

### 联调环境搭建（Windows）

#### Matlab

- 工作目录下包含接口文件和链接库
  - 接口文件路径：
    - C:\Program Files\CoppeliaRobotics\CoppeliaSimEdu\programming\remoteApiBindings\matlab\matlab
  - 链接库路径：
    - C:\Program Files\CoppeliaRobotics\CoppeliaSimEdu\programming\remoteApiBindings\lib\lib\Windows
  - 参考readMe文件，将下列文件复制到工作目录下
    - remApi.m
    - remoteApiProto.m
    - simpleTest.m
    - remoteApi.dll
- 接口函数参考[官方文档](https://www.coppeliarobotics.com/helpFiles/index.html)

#### Python

- 工作目录下包含接口文件和链接库
  - 接口文件路径：
    - C:\Program Files\CoppeliaRobotics\CoppeliaSimEdu\programming\remoteApiBindings\python\python
  - 链接库路径：
    - C:\Program Files\CoppeliaRobotics\CoppeliaSimEdu\programming\remoteApiBindings\lib\lib\Windows
  - 参考readMe文件，将下列文件复制到工作目录下(其他文件根据需求添加)
    - sim.py
    - simConst.py
    - simpleTest.py
    - remoteApi.dll
- 接口函数参考[官方文档](https://www.coppeliarobotics.com/helpFiles/index.html)

## 参考资料

1. [vrep官方帮助文档，很全面很详细，纯英文](http://www.coppeliarobotics.com/helpFiles/index.html)
2. [Robot V-Rep Tutorial机器人仿真软件V-REP的教程](https://www.bilibili.com/video/BV18t411x7CB?p=1)
3. [机器人技术与机器人仿真技术](https://space.bilibili.com/19682152?spm_id_from=333.788.b_765f7570696e666f.1)
4. [手把手进行Vrep软件操作教程【简书,monkey61】](https://www.jianshu.com/p/eb3f38c0c5fa)
5. [一些基础理论的讲解【cnblog,XXX已失联】](https://www.cnblogs.com/21207-iHome/tag/V-rep/default.html?page=1 )
6. [IK Group基础讲解](https://blog.csdn.net/philthinker/article/details/79867312)
7. [Vrep机器人动力学建模仿真知乎专栏](https://zhuanlan.zhihu.com/c_156026799)

## 实验报告模板

若用Latex：模板可参考[SJTUTesis](https://github.com/sjtug/SJTUThesis)

## 备注

上述内容仅为个人理解，若有错误，欢迎指正。