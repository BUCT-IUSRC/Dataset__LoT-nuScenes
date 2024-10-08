# LoT-nuScenes: A Virtual Long-Tail Scenario Dataset for Parallel Vision and Parallel Vehicles
Yang Mi，Yunjie Ji，Keqiu Wang，Yadong Wang，Tianyu Shen*，Kunfeng Wang*

 (*Corresponding authors)  
## Framework Overview
We constructed accident scenarios in the Carla simulator under different states, including six categories of motor vehicle accidents, one category of pedestrian accidents, and combining three weather extremes, three time periods, and five categories of locations. At the same time, we collected accident events in the format of the nuScenes dataset, which is equipped with multi-sensors and a 360° view. This dataset not only fills the gap of accident scenario data, but also achieves a long-tailed normalized distribution.
## ![tu2.png](https://cdn.nlark.com/yuque/0/2024/png/46551520/1721093518067-69251208-f39c-4149-b439-52e8af386849.png#averageHue=%23e4e2de&clientId=u10cd986a-175d-4&from=drop&id=EOU1m&originHeight=858&originWidth=1801&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=1163925&status=done&style=none&taskId=ua9dc468b-271b-4740-90be-edb001645ef&title=)
## Accident Events and Annotation of Data
The seven types of accidents are: rear-end collisions, lane changes, reversing traffic, collisions at intersections and sudden pedestrian crossings. Rear-end collisions are categorised as two-vehicle rear-end collisions and multi-vehicle rear-end collisions, and lane changing is categorised as collisions with adjacent vehicles and collisions with guardrails. Meanwhile, we use the format of nuScenes dataset for accident event collection. The following is a display with labelled boxes for two-vehicle rear-end and contraflow:
<img src="./examples of LoT-nuScenes.gif" width="800px">
## Install
### Environment
Ubuntu22.04  build Carla=0.9.15   See [https://carla.readthedocs.io/en/latest/build_linux/](https://carla.readthedocs.io/en/latest/build_linux/) 
`pip install carla=0.9.15`
or [https://blog.csdn.net/weixin_46669262/article/details/139166864?spm=1001.2014.3001.5502](https://blog.csdn.net/weixin_46669262/article/details/139166864?spm=1001.2014.3001.5502)
# Contact Us
 If you have any problem about this work, please feel free to reach us out at  2022210517@buct.edu.cn.
