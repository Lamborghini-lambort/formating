# Formating
本研究是一个基于MATLAB的多机器人编队、路径规划、避障的任务研究
<br>
<br>
代码部分暂时不公开，因目前还涉及相应的成果发表，后续会进行开放，敬请谅解！
<br>
<br>
下面对目前的仿真结果进行一个展示，具体的详细的视频在assets/video有展示！
## 🎬 仿真视频演示

### 多机器人编队切换演示

<p align="center">
  <img src="https://github.com/Lamborghini-lambort/formating/blob/main/asserts/gifs/编队改变.gif" width="800" style="border-radius:8px;">
</p>

### 多机器人的复杂地形下的避障
在全局地图未知的前提条件下，我们无法预先规划全局路径，因此对于障碍物的感知一般为近场感知，具备实时性。避障策略也应该适应障碍物出现的随机性、实时性，以及传感器感知的近场特点和实时性，因此选用基于人工势场的方法以实现水下机器人的避障方法。该方法也可推广至其他类型的机器人。

<p align="center">
  <img src="https://github.com/Lamborghini-lambort/formating/blob/main/asserts/gifs/video1.gif" width="800" style="border-radius:8px;">
</p>

### 整合任务分配和机器人围捕能力的展示
研究的最终展示结果，包括从任务分配，再到各个机器人编队执行其各自的任务，期间还涉及到机器人围捕能力的改变导致的编队队形的改变。

1、首先是机器人的聚类和任务分配结果
<p align="center">
  <img src="https://github.com/Lamborghini-lambort/formating/blob/main/asserts/pictures/task_allocation.png" width="800" style="border-radius:8px;">
</p>
2、接下来是对整个围捕过程的一个仿真演示，涉及队形变换和围捕点分配

实验结果
<p align="center">
  <img src="https://github.com/Lamborghini-lambort/formating/blob/main/asserts/pictures/result.png" width="800" style="border-radius:8px;">
</p>

## 🎬 完整超长仿真视频演示
<p align="center">
  <b>水下机器人GA-APF算法 完整避障+编队+围捕仿真演示</b><br>
  <video width="800" controls="controls" style="max-width:100%;border-radius:8px;margin-top:10px;" 
  crossorigin="anonymous" playsinline>
    <source src="https://github.com/Lamborghini-lambort/formating/releases/download/formation_v1/default.mp4" type="video/mp4">
  </video><br>
</p>
播放异常请点击：<a href="https://github.com/Lamborghini-lambort/formating/releases/tag/formation_v1/default.mp4">✅ 点击播放完整视频 ✅</a>
