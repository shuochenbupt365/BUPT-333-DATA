## Abstract

Pedestrian detection is among the most frequently used preprocessing tasks in many surveillance application fields, from low level
people counting to high level scene understanding. Even though many approaches perform well at daytime with sufficient illumination,
pedestrian detection at night is a still a critical and challenging problem for video surveillance systems. To respond to this need, in 
this paper we provide an affordable solution with a near-infrared stereo network camera as well as a novel three-dimensional foreground
pedestrian detection model. Specifically, instead of using expensive thermal camera, we build a near-infrared stereo vision system with
two calibrated network cameras and near-infrared lamps. The core of the system is a novel three-dimensional cube surface model, which is
able to estimate the dynamic changes of three-dimensional geometric information of the surveillance scene, and to segment and locate 
foreground pedestrian in real-time. A free update policy for unknown points is designed for model updating, and the extracted shadow of 
pedestrian is adopted to remove foreground false alarms. To evaluate the performance of the proposed model, the system is deployed in 
several nighttime surveillance scenes. Experimental results demonstrate that our method is capable of segmenting and detecting nighttime
pedestrian in real-time under heavy occlusion. In addition, the qualitative and quantitative comparison results show that our work 
outperforms classical background subtraction approaches and recent RGB-D method, and achieves comparable performance with state-of-the-
art deep learning pedestrian detection method even with much lower hardware cost.

## Dataset

![Image](datasetnighttime.png)

Dataset can be downloaded [here](https://pan.baidu.com/s/1cB7C7c), or here. Total in size = 12.5G. 

## Demo

![Image](logo.png)

Demo video for Nighttime Foreground Pedestrian Detection based on Three-dimensional Cube Surface Model can be download [here](https://pan.baidu.com/s/1pLkc80F) or [here](http://v.youku.com/v_show/id_XMzAxODE1MTY2MA==.html?spm=a2hzp.8244740.0.0).

