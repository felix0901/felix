---
title: "FRAME: Fast Roofline Analytical Modeling and Estimation"
collection: talks
type: "Projects"
permalink: /talks/9-frame
venue: "Open-source"
date: 2021-08-20
location: "Atlanta, GA"
--- 
### Abstract
``Frame`` is a roofline cost model for DNN accelerators. We support CNNs, MLPs, and Transformers workload.

What it does:
* Given DNN accelerator system information (using the `System` class in `src/system.py`), where you can specify PE array shape (mxu_shape), on-chip BWs, off-chip BWs, etcs.
* Given DNN workload (e.g., `model='vgg16'`)

``FRAME`` generate a table of layer-wise latency and memory usage information as well as a roofline figure, as shown in the following

![img_9.png](img_9.png)

---
### Code available
[FRAME Github Repo](https://github.com/maestro-project/frame)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maestro-project/frame/blob/master/notebook/dnn_accel_playground-run-on-colab.ipynb)
[![IMAGE ALT TEXT HERE](img_8.png)](https://github.com/maestro-project/frame)
