# SJTU_GVI
A GNSS-Visual-IMU Dataset for SLAM

Project Authors: Jie Yin

This is part of the dataset for tests in paper [M2C-GVIO](https://satellite-navigation.springeropen.com/articles/10.1186/s43020-023-00102-9)
Different from M2DGR, this dataset has following features:

1.More light-weight and easy for downloading.

2.Recoreded on a real car with high speed.

3.GNSS raw measurements are captured by a Ublox ZED-F9P receiver, which facilitate the GNSS-SLAM research.

Please give us a star if this project is helpful to your research. Thank you! If you use M2DGR in an academic work, please cite:

~~~
@ARTICLE{9664374,
  author={Yin, Jie and Li, Ang and Li, Tao and Yu, Wenxian and Zou, Danping},
  journal={IEEE Robotics and Automation Letters}, 
  title={M2DGR: A Multi-sensor and Multi-scenario SLAM Dataset for Ground Robots}, 
  year={2021},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/LRA.2021.3138527}}

@article{hua2023m2c,
  title={M2C-GVIO: motion manifold constraint aided GNSS-visual-inertial odometry for ground vehicles},
  author={Hua, Tong and Pei, Ling and Li, Tao and Yin, Jie and Liu, Guoqing and Yu, Wenxian},
  journal={Satellite Navigation},
  volume={4},
  number={1},
  pages={1--15},
  year={2023},
  publisher={SpringerOpen}
}
~~~

<div align=center>

<img src="https://github.com/sjtuyinjie/SJTU_GVI/blob/main/data/bigcar2.jpg" width="800px">
</div>

<p align="center">Figure 1. A picture of our acquisition platform.</p>



<div align=center>

<img src="https://github.com/sjtuyinjie/SJTU_GVI/blob/main/data/bdcalib.jpg" width="800px">
</div>
<p align="center">Figure 2. We were calibrating the extrinsics.</p>

## 1.Sequence 
The extraction code is "yj66"


Sequence|Collection Date|Total Size|Duration|Rosbag
--|:--|:--:|--:|--:
Seq1|2021-12-23|2.37G|349s|[Rosbag](https://pan.baidu.com/s/1qoFsvOUyJCf7xi6KHBBoCQ)
Seq2|2021-12-23|921M|109s|[Rosbag](https://pan.baidu.com/s/15usabuNPmlmC_S4cQsGIYg)
Seq3|2021-12-23|1.19G|146s|[Rosbag](https://pan.baidu.com/s/1AfoDweqbo89PDl6ef0mYZA)
Seq4|2021-12-23|850M|112s|[Rosbag](https://pan.baidu.com/s/1uc6RLjXhjs15g7Czg_JTDA)
Seq5|2021-12-23|1.26G|159s|[Rosbag](https://pan.baidu.com/s/1vlE16qNDnV4C2i-cfg6NVQ)
## 2.Calibration
The camera intrinsic and cam-imu extrinsics calibration results is given in [Link](https://github.com/sjtuyinjie/SJTU_GVI/tree/main/calibrations)
## 3.Ground Truth
The ground truth of the datasets is given in [Link](https://github.com/sjtuyinjie/SJTU_GVI/tree/main/data)



## 4.ACKNOWLEGEMENT
Authors express our appreciation for the support of Shanghai West Hongqiao Navigation Technology Co., LTD.
