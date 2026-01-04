# Formating
本研究是一个基于MATLAB的多机器人编队、路径规划、避障的任务研究


代码部分暂时不公开，因目前还涉及相应的成果发表，后续会进行开放，敬请谅解！


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
<p align="center">
  <b>水下机器人GA-APF算法 完整避障+编队+围捕仿真演示</b><br>
  <video width="800" controls="controls" style="max-width:100%;border-radius:8px;margin-top:10px;">
    <source src="https://private-user-images.githubusercontent.com/174073694/531716823-49aa56f9-5a8b-44b5-83ec-6abc22c0e7db.mp4?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Njc1MjM1MzcsIm5iZiI6MTc2NzUyMzIzNywicGF0aCI6Ii8xNzQwNzM2OTQvNTMxNzE2ODIzLTQ5YWE1NmY5LTVhOGItNDRiNS04M2VjLTZhYmMyMmMwZTdkYi5tcDQ_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMTA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDEwNFQxMDQwMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kZjNjMjI0ZmE3NWU4YWZjNjYxZDU2NTEyYTBhMTJlMzQ0YmNlMzFhOTNkMTc0NTU2YmQ4ODFhNWQ0ODU5NzgxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.giPSi_pc02beW792OG-0M9DuvzWl2oWk-sGMvgBj-Qc" type="video/mp4">
    若播放异常，请点击查看：<a href="https://private-user-images.githubusercontent.com/174073694/531716823-49aa56f9-5a8b-44b5-83ec-6abc22c0e7db.mp4?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Njc1MjM1MzcsIm5iZiI6MTc2NzUyMzIzNywicGF0aCI6Ii8xNzQwNzM2OTQvNTMxNzE2ODIzLTQ5YWE1NmY5LTVhOGItNDRiNS04M2VjLTZhYmMyMmMwZTdkYi5tcDQ_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMTA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDEwNFQxMDQwMzdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kZjNjMjI0ZmE3NWU4YWZjNjYxZDU2NTEyYTBhMTJlMzQ0YmNlMzFhOTNkMTc0NTU2YmQ4ODFhNWQ0ODU5NzgxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.giPSi_pc02beW792OG-0M9DuvzWl2oWk-sGMvgBj-Qc">完整仿真视频</a>
  </video>
</p>

