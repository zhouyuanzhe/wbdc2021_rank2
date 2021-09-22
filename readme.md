单模型应该能拿复赛B榜第二。融合没融好


* 队友的模型、建模方式比较独到，更有学习价值
* 几乎无手工特征
* DCNv1
* 模型没调参过，精调参可能有进一步提升
* 加入初赛数据有一定提升
* 加测试集数据有提升
* no trick，不盲目崇拜高级模型，好好做好基础就行，数据为本
* end2end向量比预训练向量的效果更好
* 结合end2end和预训练向量有一定提升
* embedding layer 比 generator 更好用


和其他队伍重合的实验结果：
* sigmoid作为gate效果更好
* MMoE与线上分数更接近，DCN分数线下虚高
* 完播率直接等权重加进去没用，因为这里预估的是CTR，目标不一致。

![image](https://user-images.githubusercontent.com/39345674/134325467-69659b15-9ffe-46ec-b2df-93469693b005.png)

