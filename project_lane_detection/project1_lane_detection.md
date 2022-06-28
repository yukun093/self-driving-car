## 项目一 车道线检测

本着秋招的目的,将以前学过的自动驾驶的理论知识和编程语言进行融合,加强一下理论和编码能力,理论主要包括运动规划, 状态预测和定位,视觉感知. 所用的内容主要来自Udacity, 以及搜集到的一些论文,博客和其他来源知识将其进行汇总, 使得知识体系更完整.

语言主要用python和c++.

### 前言

首先车道线的数据集是图片和视频, 对图片中的车道线进行检测, 和对图片中的车道线进行实施检测.

一个车道线检测基本包括以下内容:

Gray Scale Transformation 灰度图转换

Gaussian Smoothing 高斯润滑

Canny edge detection (Canny 边缘检测)

基于ROI的边缘过滤(definition of ROI: A **region of interest** (often abbreviated **ROI**), are samples within a [data set](https://en.wikipedia.org/wiki/Data_set) identified for a particular purpose(from Wikipedia))

hough transformation 霍夫变换

lane extrapolation 车道外推

### 测试数据集

image data:

![data_lane_lines](/home/yukun/Pictures/data_lane_lines.png)

video data:

<video src="/home/yukun/Documents/self-driving-car/project_lane_detection/data/test_videos/solidWhiteRight.mp4"/>

### 代码

基础版车道线检测<sup><a href="lanes detection">2</a></sup>

详细的github的车道线检测代码可以参考这篇文章里的<sup><a href="Towards end-to-end lane detection: an instance segmentation approach">1</a></sup>













### 参考文献

```html
<sup><a href="Towards end-to-end lane detection: an instance segmentation approach">1</a></sup>
<span name = "Towards end-to-end lane detection: an instance segmentation approach">.</span>
```

Neven, Davy, et al. "Towards end-to-end lane detection: an instance segmentation approach." *2018 IEEE intelligent vehicles symposium (IV)*. IEEE, 2018.

```html
<sup><a href="lanes detection">2</a></sup>
<span name = "lanes detection">.</span>
```

https://zhuanlan.zhihu.com/p/25354571