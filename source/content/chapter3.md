# 3 
## 3.1 量化基础EDA（SCL）
SCL产生的基线是不断变化的，换言之，个体的基础SCL信号是持续变化的，彼此之间也可能差异显著。因此，不能简单对SCL信号进行平均化处理来量化SCL，平均数可能会包含SCR，导致高估真实的SCL值，这种方式量化的结果很难判断被试的整体SCL水平是高是低。\
研究者在量化SCL信号前，需从基础信号中减去相位信号（SCR）的振幅，或是在未产生SCR的周期中测量，这样得出的基线更加真实可靠。在研究SCL时，常见的操作是对信号进行归一化，即人为设定一条SCL信号作为基准，然后对同一被试进行不同操作，比较产生的SCL信号与基准信号之间的相对差值，不考虑绝对差值。

![](https://raw.githubusercontent.com/evelyn046/EDAmanual_test/master/source/picture/normalization.png)
<center>线性归一化公式</center>

![](https://raw.githubusercontent.com/evelyn046/EDAmanual_test/master/source/picture/meannormalization.png)
<center>均值归一化公式</center>
此外，建议对NS-SCRs频率（静息状态下通常为1-3次/分钟，高唤醒状态下超20次/分钟）以及NS-SCRs的峰值振幅进行测量，原因如下：

* 这些分量可直接参与计算，前提是测量不同被试或不同条件时要选择固定的测量时间尺度。
* 一些较早的研究发现，SCL随着NS-SCRs频率的增加而下降，但之后研究者们同样发现，当被试处于高唤醒状态时，NS-SCRs频率会显著增加，尽管对于NS-SCRs的频率/振幅能否直接代替传统SCL信号一直争议不断，但至少可以将其看成反映唤醒程度的指标之一。（注：在高唤醒状态下，NS-SCRs可能会连续产生或相互叠加。）

## 3.2 量化相位EDA（SCR）
在测量EDA的实验中，首先要制定一个标准来确定得到的SCR信号是事件相关的还是非特异性的。如果标准制定过于宽松，可能会导致误将NS-SCR视为ER-SCR一并分析，误认为这些值与实验操作有关。如果标准制定过于严格，会导致许多ER-SCR被错误分至NS-SCR一类过滤掉，结果无法达到预期标准。
