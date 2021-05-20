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
