paddle ocr项目的个人笔记

查看主页中的各类标签

ocr-overview：ocr算法的一些记录

practice：跑的一些作业


算法结构主要分为文本检测部分和文字识别部分（附带文本框矫正部分用来适应某些不规则文本的场景）
文本检测采用基于分割的DB算法，文本识别采用主流的CRNN

文本框识别

![image](https://user-images.githubusercontent.com/50852027/154205585-2ec6555c-b451-4de5-97d7-50fa25cb8971.png)

文字识别输出

![image](https://user-images.githubusercontent.com/50852027/154206098-d7c1dc99-b1fd-489f-9e3e-14591b424920.png)

文本检测部分算法主要有基于回归：文本检测方法和目标检测算法的方法相似，文本检测方法只有两个类别，图像中的文本视为待检测的目标，其余部分视为背景（CTPN）

                        分割：通过分割方法得到图像中文本区域，再利用opencv，polygon等后处理得到文本区域的最小包围曲线。

文本检测算法属于目标检测算法的子集，常见目标检测算法有RCNN、YOLO、SSD系列





#还在慢慢写中。。。。。。。。。。。。。。。。。。。。。


