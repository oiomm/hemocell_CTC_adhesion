这是A Lattice Boltzmann Study of the Transport and Adhesion of Deformable Circulating Tumor Cells in Bifurcated Microvessels文章的程序文件以及数据文件。  
程序文件使用方法：  
  安装HemoCell参考HemoCell官方链接：https://github.com/UvaCsl/HemoCell  
  program文件内容覆盖到HemoCell/examples/case_bif  
  case_bifurcatedvessel.cpp  -  主程序：这个程序是对单个CTC在对称分叉血管中流动粘附仿真脚本  
  config.xml  -  仿真参数设置文件：设置用于准备流场的预热迭代次数、定义数据存储、日志记录和检查点的输出目录、控制粒子材料模型和粒子位置相对于流体时间步长的更新频率、使用.stl文件定义仿真域的几何形状、  
  设置流体的密度、粘度，空间分辨率、时间步长和雷诺数、义颗粒相互作用的排斥常数、定总迭代次数（tmax）以及写入数据和检查点的间隔、设置与仿真网格内粘度相关的参数。  
  CTC.pos  -  CTC个数与位置  
  CTC.xml  -  CTC本构模型参数设置，描述了CTC的几何尺寸以及硬度。  
  tube.stl  -  血管的几何结构文件  
数据文件：  
  paraview后处理软件的标准数据格式文件，可以直接导入查看。  
  https://github.com/Kitware/ParaView  
These are the program and data files for the article "A Lattice Boltzmann Study of the Transport and Adhesion of Deformable Circulating Tumor Cells in Bifurcated Microvessels".  

Instructions for using the program files:  
Install HemoCell by referring to the official HemoCell link: https://github.com/UvaCsl/HemoCell  
The contents of the program folder should be copied over to HemoCell/examples/case_bif.  
Files:  
case_bifurcatedvessel.cpp - Main program: This is the simulation script for the flow and adhesion of a single CTC in a symmetrical bifurcated blood vessel.  
config.xml - Simulation parameter configuration file: Sets the number of warm-up iterations for preparing the fluid field, defines output directories for data storage, logging, and checkpoints, controls the update frequency of the particle material model and particle positions relative to the fluid time step, defines the geometry of the simulation domain using an .stl file, sets fluid density, viscosity, spatial resolution, time step, Reynolds number, particle interaction repulsion constants, total iterations (tmax), data writing and checkpoint intervals, and parameters related to viscosity inside the simulation grid.  
CTC.pos - CTC count and positions.  
CTC.xml - Constitutive model parameters for CTC, describing the geometry and stiffness of the CTC.  
tube.stl - Geometry file for the blood vessel.  
Data files:  
Standard data format files for ParaView post-processing software, which can be directly imported for viewing. https://github.com/Kitware/ParaView  
