# Overview

TensorFlow was designed to be a good deep learning solution for mobile platforms. Currently we have two solutions for deploying machine learning applications on mobile and embedded devices: TensorFlow for Mobile and TensorFlow Lite.

TensorFlow Lite versus TensorFlow Mobile

Here are a few of the differences between the two:

TensorFlow Lite is an evolution of TensorFlow Mobile. In most cases, apps developed with TensorFlow Lite will have a smaller binary size, fewer dependencies, and better performance.
TensorFlow Lite is in developer preview, so not all use cases are covered yet. We expect you to use TensorFlow Mobile to cover production cases.
TensorFlow Lite supports only a limited set of operators, so not all models will work on it by default. TensorFlow for Mobile has a fuller set of supported functionality.
TensorFlow Lite provides better performance and a small binary size on mobile platforms as well as the ability to leverage hardware acceleration if available on their platforms. In addition, it has many fewer dependencies so it can be built and hosted on simpler, more constrained device scenarios. TensorFlow Lite also allows targeting accelerators through the Neural Networks API.

TensorFlow Lite currently has coverage for a limited set of operators. While TensorFlow for Mobile supports only a constrained set of ops by default, in principle if you use an arbitrary operator in TensorFlow, it can be customized to build that kernel. Thus use cases which are not currently supported by TensorFlow Lite should continue to use TensorFlow for Mobile. As TensorFlow Lite evolves, it will gain additional operators, and the decision will be easier to make.

<hr />
Except as otherwise noted, the content of this page is licensed under the Creative Commons Attribution 3.0 License, and code samples are licensed under the Apache 2.0 License. For details, see our Site Policies. Java is a registered trademark of Oracle and/or its affiliates.

上次更新日期：十一月 14, 2017
