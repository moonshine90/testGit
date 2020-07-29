%   The 3D Dense Face Alignment (3DDFA) Project
%   ==========
%   The Code is created based on the method described in the following paper:
%   [1] "Face Alignment across Large Poses A 3D Solution", 
%        Xiangyu Zhu, Zhen Lei, Xiaoming Liu, Hailin Shi and Stan Z. Li
%        IEEE Conference on Computer Vision and Pattern Recognition (CVPR),
%        2016
%
%   The code and the algorithm are for non-comercial use only.
%
%  
%   Author: Xiangyu Zhu (frank.xy.zhu@gmail.com)
%   Date  : 05/04/2016
%   Copyright 2016, Center for Biometrics and Security Research & 
%   National Laboratory of Pattern Recognition,
%   Institute of Automation, Chinese Academy of Sciences,
%   ==========


How to install the code:
1. Downloading the Basel Face Model (BFM) on "http://faces.cs.unibas.ch/bfm/main.php?nav=1-0&id=basel_face_model"
2. Copy the "01_MorphableModel.mat" file in the BFM to Matlab/ModelGeneration/
3. Run the Matlab/ModelGeneration/ModelGenerate.m to generate the shape model "Model_Shape.mat" and copy it to the Matlab/


How to use the code:
1. Go to Matlab/
2. Run "Step1.m to Step8.m"
