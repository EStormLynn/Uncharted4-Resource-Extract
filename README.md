# Uncharted4-Resource-Extract
Extract game resource from ps4 game: Uncharted 4: A Thief's

详细介绍可以参考这篇文章：
https://zhuanlan.zhihu.com/p/232139156

## 文件说明

    ├─1.PS4PKGViewer.v1.5-LMAN	 pkg提取
    │      PS4PKGViewer.bin
    │      PS4PKGViewer.dat
    │      PS4PKGViewer.exe
    │      Readme.txt
    │
    ├─2.PSArcTool				psarc文件提取
    │      PSArcTool.exe
    │
    ├─3.Uncharted4 				神海资源提取
    │      Uncharted4.exe
    │      Uncharted4_m.exe
    │
    └─4.blender 				blender导入支持 .smd
            blender_source_tools_3.1.0.zip


## 使用说明

### 1.PS4PKGViewer
* 打开File->Open 选择游戏的pkg
* Extra-> ListContent 显示文件目录
* 目录结构下右键文件夹Extract to

### 2.PSArcTool

把psARC文件和PSArcTool.exe 放在同一目录下，选择.psARC文件拖动到PSArcTool.exe上，提取相应的资源到当前文件夹下。

### 3.Uncharted4

直接拖动.pak文件到Uncharted4.exe上即可，结束后，当前路径会输出这个pak解出来的资源，

### 4.blender 

* Select Edit > User Preferences
* Move to the Addons tab
* Click Install... at the top of the window
* Find the downloaded zip file
