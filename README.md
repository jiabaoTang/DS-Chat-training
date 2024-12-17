# DS-Chat-training

> 相应文档：[使用 DeepSpeed 微调 OPT 基础语言模型](https://blog.csdn.net/weixin_43254181/article/details/144494212)

[TOC]

## 第 1 次提交

> 2024-12-17 | 1 | zjma

根据我们的实验需要，修改了 [DeepSpeed-Chat](https://github.com/microsoft/DeepSpeedExamples/tree/master/applications/DeepSpeed-Chat) 的文件结构和部分代码。

当前的目录结构为：

```
├── dschat
│   └── utils
├── README.md
└── step1_supervised_finetuning
    ├── Dahoas      # dataset
    ├── facebook    # pre-trained model
    ├── main.py
    ├── training_scripts
    └── yitingxie   # dataset
```

运行脚本方式：

1、下载该仓库。

```
git clone https://github.com/zhulu506/DS-Chat-training.git
```

2、准备预训练模型和数据集。

3、运行脚本。

```
pwd # DS-Chat-training/step1_supervised_finetuning
bash training_scripts/my_test/run_opt-125m.sh
```
