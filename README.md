# LoT-nuScenes: A Virtual Long-Tail Scenario Dataset for Parallel Vision and Parallel Vehicles
Yang Mi，Yunjie Ji，Keqiu Wang，Yadong Wang，Tianyu Shen*，Kunfeng Wang*
 (*Corresponding authors)  
## Framework Overview
We constructed accident scenarios in the Carla simulator under different states, including six categories of motor vehicle accidents, one category of pedestrian accidents, and combining three weather extremes, three time periods, and five categories of locations. At the same time, we collected accident events in the format of the nuScenes dataset, which is equipped with multi-sensors and a 360° view. This dataset not only fills the gap of accident scenario data, but also achieves a long-tailed normalized distribution.
## ![tu2.png](https://cdn.nlark.com/yuque/0/2024/png/46551520/1721093518067-69251208-f39c-4149-b439-52e8af386849.png#averageHue=%23e4e2de&clientId=u10cd986a-175d-4&from=drop&id=EOU1m&originHeight=858&originWidth=1801&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=1163925&status=done&style=none&taskId=ua9dc468b-271b-4740-90be-edb001645ef&title=)
## Accident Events
The seven incidents were: rear-end, lane-changing, drive in the wrong direction, collision at an intersection, and sudden pedestrian crossing. Rear-end collisions are divided into two-vehicle rear-end collisions and multi-vehicle rear-end collisions, and lane changes are divided into collisions with neighbouring vehicles and collisions with guardrails. From (a) to (i), different events in different scenes are shown. (a) and (b) show a two-vehicle rear-end and a multi-vehicle rear-end, respectively, (c) and (d) show collisions with neighboring vehicles and guardrails while changing lanes, (e) and (f) show vehicles traveling in the opposite direction, (g) and (h) show intersection collisions, and (i) shows a sudden pedestrian approach.
![16e6faa6440081d5ec6b3e33916de73.png](https://cdn.nlark.com/yuque/0/2024/png/46551520/1721115725843-d21c7ef6-a5f1-476f-9f39-8e30e8a4fb2c.png#averageHue=%235a6247&clientId=u1ead93a6-74f8-4&from=paste&height=438&id=u21801b3d&originHeight=657&originWidth=985&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=1115369&status=done&style=none&taskId=ud1b0d76b-ae10-4953-98c9-8e54c949e9a&title=&width=656.6666666666666)
## Annotation of Data
We collected the above events using the nuScenes dataset format with four annotation types, car, truck, cyclist, and pedestrian. The labelling is shown in the figure below. The yellow box in the label is car, blue is motorcycle, orange is truck and green is pedestrian.
![biandao+zhuiwei.png](https://cdn.nlark.com/yuque/0/2024/png/46551520/1721117610919-6d6d9dd4-a71d-421a-807c-66ae6c9b7f19.png#averageHue=%238b958e&clientId=u1ead93a6-74f8-4&from=drop&id=u17b90a26&originHeight=625&originWidth=1903&originalType=binary&ratio=1.5&rotation=0&showTitle=false&size=1305579&status=done&style=none&taskId=udd6a8677-5380-45b4-b55c-fd948397859&title=)
## Install
### Environment
Ubuntu22.04  build Carla=0.9.15   See [https://carla.readthedocs.io/en/latest/build_linux/](https://carla.readthedocs.io/en/latest/build_linux/)
# Contact Us
 If you have any problem about this work, please feel free to reach us out at  2022210517@buct.edu.cn.
