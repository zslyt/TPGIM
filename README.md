# TPGIM1.0
Author: Sheng Zeng
% E-mail: shengzeng@stumail.nwu.edu.cn   
%         zs416227094@163.com
This Matlab code is the explanation of the following paper:
A novel geometry image to accurately represent a surface by preserving mesh topology


1.Prerequisites for Deployment 

Verify that version 9.4 (R2018a) of the MATLAB Runtime is installed.   
Alternatively, download and install the Windows version of the MATLAB Runtime for R2018a 
from the following link on the MathWorks website:

    http://www.mathworks.com/products/compiler/mcr/index.html
    
 Run main.exe directly 
  
2. Description
 | Function | Description |
 | :--------| :---------- |
 | Open 3D mesh                             | - Displays the original 3D model |
 | Generating TPGIM from 3D models          | - Tpgim is generated from 3D mesh with halfedge structure |
 | Reconstruction from TPGIM                | - Reconstruct 3D mesh from image |
 | Import cutting path(for faild mesh)      | - Manual solution for failed examples |
 | 3D mesh segmentation demo using TPGIM    | - A Demo of using IVC to segment 3D model |
 
 3 Tips
   Please open the 3D mesh  before generating tpgim.
   Please do not change the name of the default folder.
   When using reconstruction from TPGIM, copy tpgim and related files to "2Dtpgim" folder for operation.
   We provide sample data. If you use new data, please follow the above rules.
   The larger the model, the longer the running time. See Table 2 in the paper for the running time.
   The console window allows you to view the running steps.
