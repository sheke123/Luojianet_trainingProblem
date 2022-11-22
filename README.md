# LuojiaNet_mindspore训练问题描述
## Problem1问题描述：
在进行验证时，各个卡的同一个Epoch的验证精度不一致。

ModelArts任务ID：685e2429-307d-4728-99e9-ff4e783f9822

## Problem2问题描述：
在一次8卡训练任务中，部分卡已经完成了训练设定的Epoch，而部分卡还在训练的中途，导致训练报错终止。该问题是偶然重建出现，无法刻意复现。

ModelArts任务ID：0dcce741-67f7-49b2-9b6b-7f0a1dae2cd4

## Problem3问题描述：
在训练DenseNet121网络时，当BatchSize设置较大（例如16，32，64）时，会出现内存溢出，导致训练报错终止。

ModelArts任务ID：868dc355-ddfa-42b8-bfe1-db930123bb9d
