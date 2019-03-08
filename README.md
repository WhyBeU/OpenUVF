# OpenUVF
Copyright © 2019 Southern Company Services, Inc. All rights reserved. OpenUVF is [licensed](https://github.com/southern-company-r-d/OpenUVF/blob/master/LICENSE) under the Apache License, Version 2.0.

OpenUVF uses portions of [TensorFlow](http://www.tensorflow.org) ([TensorFlow on GitHub](https://github.com/tensorflow/tensorflow)), also licensed under [Apache 2.0](https://github.com/tensorflow/tensorflow/blob/master/LICENSE), copyright 2018 The TensorFlow Authors.

## Overview

OpenUVF is a software utility developed by Southern Company R&D, a subdivision of Southern Company Services, Inc., to automatically analyze Ultraviolet Fluorescence (UVF) images of solar PV modules. It is imagined as a foundation, upon which UVF can be developed as a practical inspection technique complementing existing PV inspection techniques like Electroluminescence and Thermography.

OpenUVF is intended for research and development purposes. It is a work in progress, and may not work for your application or on your system. We hope you find it useful, though!

This software requires the following items:
* MATLAB (and the Image Processing Toolbox)
* [LabelImg](https://github.com/tzutalin/labelImg) or a similar annotation tool with PASCAL VOC format
* Python 3, Anaconda, and several packages described in our documentation [here](https://github.com/southern-company-r-d/OpenUVF/tree/master/docs).
* [TensorFLow](https://github.com/tensorflow/tensorflow), and for training new models, NVIDIA GPU hardware and described in our documentation [here](https://github.com/southern-company-r-d/OpenUVF/tree/master/docs).
* And additional items described in our documentation [here](https://github.com/southern-company-r-d/OpenUVF/tree/master/docs).

A portion of TensorFlow, specifically the [Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection), is redistributed with OpenUVF. It is included in our code [here](https://github.com/southern-company-r-d/OpenUVF/tree/master/core/object_detection).

## Details
More detailed documentation is in the works. For now, check out what we have [here](https://github.com/southern-company-r-d/OpenUVF/tree/master/docs).

## Disclaimer
As set forth in the [license](https://github.com/southern-company-r-d/OpenUVF/blob/master/LICENSE), Southern Company Services, Inc., provides OpenUVF on an “as is” basis, without warranties or conditions of any kind, either express or implied, including, without limitation, any warranties or conditions of title, non-infringement, merchantability, or fitness for a particular purpose. You (the individual or legal entity exercising permissions granted by this license) are solely responsible for determining the appropriateness of using or redistributing OpenUVF and assume any risks associated with your exercise of permissions under this license.
