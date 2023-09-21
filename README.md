# BlenderRender
 功能：在blender里将fbx文件和音频文件批量渲染成视频

使用：

1. 需先在blender python里安装相关的包，安装教程参考 https://zhuanlan.zhihu.com/p/546532034

（1）cd "C:\Program Files\Blender Foundation\Blender 3.1\3.1\python"

（2） .\bin\python.exe -m pip install <你要安装的python module> --target=.\lib\site-packages

2. 在代码里修改fbx文件夹位置, 音频文件夹位置，输出的视频文件位置，以及导入fbx模型在场景中的坐标(视渲染结果修改)

(1) Line6: fbx文件夹位置

(2) Line7: 音频文件夹位置

(3) Line8: 视频文件夹位置

(4) Line39: 修改fbx的location(如果渲染模型不在视野中，则需要修改)
