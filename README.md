# SimpleRenderingProcess

#### 介绍
Eigen写简单渲染流程


#### 使用说明  
mkdir build   
cd build    
cmake ..   
make    

####运行程序  

texture: 使用代码中的 texture shader.  
  ./Rasterizer output.png texture  
normal: 使用代码中的 normal shader.  
  ./Rasterizer output.png normal  
phong: 使用代码中的 blinn-phong shader.  
  ./Rasterizer output.png phong  
bump: 使用代码中的 bump shader.  
  ./Rasterizer output.png bump  
displacement: 使用代码中的 displacement shader.  
  ./Rasterizer output.png displacement  


之前工作的开发环境为Linux。安装好opencv2和Eigen库就可运行。现在在windows上反而麻烦，在这里提供课程链接和环境已经装好的虚拟机链接
   

计算机图形学与混合现实在线平台：https://games-cn.org/intro-graphics/ （全是精英中的精英。 内容都是开源免费的，获取知识的好平台）
虚拟机：https://pan.baidu.com/s/198u7ETgY7h24IuYCYslmlw 密码:p085