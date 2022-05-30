## 该文件夹是用来存放模式识别作业中Self-attention可视化的脚本
### 介绍
* （1）通过Grad_CAM的方法实现Self-attention可视化。
* （2）执行时需要导入对应网络（应用Self-attention机制的网络）的模型文件。
* （3）结果示例请见对应的Grad_CAM_1.png和Grad_CAM_3.png。
* （4）参考文献及代码库请见下文。
### 参考文献及代码库链接：
* [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](https://arxiv.org/abs/1610.02391)
* [Grad-CAM代码库](https://github.com/jacobgil/pytorch-grad-cam)
### 文件类型介绍：
```
├── grad_cam_utils.py（定义Grad_CAM执行单元）  
└── grad_cam_vit.py（针对vision_transformer模型的Grad_CAM执行脚本） 
```
### 信息及维护时间：
```
作者：林飞
创建：2022-05-17
更新：2022-05-22
用途：Self-attention可视化。
```
