# Formating
本研究是一个基于MATLAB的多机器人编队、路径规划、避障的任务研究


代码部分暂时不公开，因目前还涉及相应的成果发表，后续会进行开放，敬请谅解！


下面对目前的仿真结果进行一个展示
## 🎬 仿真视频演示

### 多机器人编队切换演示

<p align="center">
  <img src="https://github.com/Lamborghini-lambort/formating/blob/main/asserts/gifs/编队改变.gif" width="800" style="border-radius:8px;">
</p>

### 多机器人的复杂地形下的避障
在全局地图未知的前提条件下，我们无法预先规划全局路径，因此对于障碍物的感知一般为近场感知，具备实时性。避障策略也应该适应障碍物出现的随机性、实时性，以及传感器感知的近场特点和实时性，因此选用基于人工势场的方法以实现水下机器人的避障方法。该方法也可推广至其他类型的机器人。

<center>
  <figure>
    <figcaption>多机器人避障 </figcaption>
    <!-- 视频嵌入：src 填你的 GitHub 附件链接，可自定义宽度/控制栏 -->
    <video width="80%" controls title="这里也可以加悬浮提示标题">
      <source src="https://github.com/user-attachments/assets/91399082-0263-49f7-9fc1-fd5e75092883" type="video/mp4">
      你的浏览器不支持视频播放，请点击链接查看：<a href="https://github.com/user-attachments/assets/91399082-0263-49f7-9fc1-fd5e75092883">视频链接</a>
    </video>
  </figure>
</center>


### 整合任务分配和机器人围捕能力的展示
研究的最终展示结果，包括从任务分配，再到各个机器人编队执行其各自的任务，期间还涉及到机器人围捕能力的改变导致的编队队形的改变。
https://github.com/user-attachments/assets/91399082-0263-49f7-9fc1-fd5e75092883

