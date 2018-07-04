# Caricature-Data
This repository contain the caricature images with corresponding landmark in paper: <a href="https://arxiv.org/abs/1803.06802v2">Alive Caricature from 2D to 3D</a>. 

The **Caricature_w_landmark** folder contains the caricature images with its landmarks. We named them by number. e.g. 1.jpg with its landmarks file named 1.txt.

Each text file was organized by x-coordinate and y-coordinate of 68 landmarks. The sequence of landmarks following 
<a href="https://ibug.doc.ic.ac.uk/media/uploads/images/annotpics/figure_68_markup.jpg"> ibug_facial_landmarks.jpg</a>

We provide a python script to read the landmarks file and display them. 

Usage: run **read_landmarks.py** in this folder. For example, you want to show the 7-th image's landmarks, you can use:
``` bash
cd ../Caricature_w_landmark
python read_landmarks.py --index 7
```
Dependencies: PIL. 

It should be something like this. Those red points are facial landmarks.

<img src = "example.png" height = "550px"/>

The **my_result_Crop** folder contains outputs given by our method. 

# Usage
If you have comments or questions, please contact Qianyi Wu (wqy9619@mail.ustc.edu.cn) and Juyong Zhang (juyong@ustc.edu.cn).

# License
Please note that this dataset could be used for research purpose only, and any commercial use of the data is prohibited.

# Citation
Please cite the following paper if this dataset helps your research:
<a href="https://arxiv.org/abs/1803.06802v2">Alive Caricature from 2D to 3D</a>

    @article{wu2018alive
          title={Alive Caricature from 2D to 3D},
          author={Wu, Qianyi and Zhang, Juyong and Lai, Yu-Kun and Zheng, Jianmin and Cai, Jianfei}
          journal={CVPR},
          year={2018}
    }

