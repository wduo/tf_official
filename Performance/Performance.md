# Performance

Performance is often a significant issue when training a machine learning model. This section explains various ways to optimize performance. Start your investigation with the Performance Guide and then go deeper with techniques detailed in High-Performance Models:

Performance Guide, which contains a collection of best practices for optimizing your TensorFlow code.
High-Performance Models, which contains a collection of advanced techniques to build highly scalable models targeting different system types and network topologies.
Benchmarks, which contains a collection of benchmark results.
XLA (Accelerated Linear Algebra) is an experimental compiler for linear algebra that optimizes TensorFlow computations. The following guides explore XLA:

XLA Overview, which introduces XLA.
Broadcasting Semantics, which describes XLA's broadcasting semantics.
Developing a new back end for XLA, which explains how to re-target TensorFlow in order to optimize the performance of the computational graph for particular hardware.
Using JIT Compilation, which describes the XLA JIT compiler that compiles and runs parts of TensorFlow graphs via XLA in order to optimize performance.
Operation Semantics, which is a reference manual describing the semantics of operations in the ComputationBuilder interface.
Shapes and Layout, which details the Shape protocol buffer.
Using AOT compilation, which explains tfcompile, a standalone tool that compiles TensorFlow graphs into executable code in order to optimize performance.
And finally, we offer the following guide:

How to Quantize Neural Networks with TensorFlow, which can explains how to use quantization to reduce model size, both in storage and at runtime. Quantization can improve performance, especially on mobile hardware.

<hr />
Except as otherwise noted, the content of this page is licensed under the Creative Commons Attribution 3.0 License, and code samples are licensed under the Apache 2.0 License. For details, see our Site Policies. Java is a registered trademark of Oracle and/or its affiliates.

上次更新日期：十一月 2, 2017
