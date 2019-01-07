# TensorFlow Notebook

A pre-configured and fully integrated minimal runtime environment with TensorFlow, an open source software library for machine learning, Keras, an open source neural network library, Jupyter Notebook, a browser-based interactive notebook for programming, mathematics, and data science, and the Python programming language.

The stack is built in several variations with different hardware optimization features: OpenBLAS and Intel MKL for x86 CPU, and CUDA for NVidia GPU.

### Tagging policy

Tag format:

```
tensorflow-notebook:<tensorflow_version>-python<python_version>-keras<keras_version>-<optimization>-<operating_system>
```

Versions available:

* TensorFlow versions: **1.12.0**, 1.11.0, 1.10.0, 1.9.0, 1.8.0, 1.7.0, 1.6.0, 1.5.0, 1.4.1, 1.3.0
* Python versions: **3.6.3**, 2.7.14
* Keras versions: **2.2.4**, 2.2.2, 2.1.6, 2.0.2, 1.2.2
* Optimizations: **cpu**, cpu_mkl, cuda9, cuda10
* Operating systems: **alpine3.8**, ubuntu18.04, debian9, centos7

### Actual tags

#### `latest`

* Full tag alias: `1.12.0-python3.6.3-keras2.2.4-cpu-alpine3.8`
* Software: TensorFlow 1.12.0, Keras 2.2.4, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/tensorflow112_keras22_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/tensorflow112_keras22_python36_mkl_notebook-190103?us=dockerhub)

#### `latest-ubuntu18.04`

* Full tag alias: `1.12.0-python3.6.3-keras2.2.4-cpu-ubuntu18.04`
* Software: TensorFlow 1.12.0, Keras 2.2.4, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/tensorflow112_keras22_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/tensorflow112_keras22_python36_mkl_notebook-190103?us=dockerhub)

#### `latest-debian9`

* Full tag alias: `1.12.0-python3.6.3-keras2.2.4-cpu-debian9`
* Software: TensorFlow 1.12.0, Keras 2.2.4, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/tensorflow112_keras22_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/tensorflow112_keras22_python36_mkl_notebook-190103?us=dockerhub)

#### `latest-centos7`

* Full tag alias: `1.12.0-python3.6.3-keras2.2.4-cpu-centos7`
* Software: TensorFlow 1.12.0, Keras 2.2.4, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/tensorflow112_keras22_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/tensorflow112_keras22_python36_mkl_notebook-190103?us=dockerhub)

#### `latest-python2`

* Full tag alias: `1.12.0-python2.7.14-keras2.2.4-cpu-alpine3.8`
* Software: TensorFlow 1.12.0, Keras 2.2.4, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/tensorflow112_keras22_python27_mkl_notebook-190103](https://jetware.io/appliances/aise/tensorflow112_keras22_python27_mkl_notebook-190103?us=dockerhub)

#### `latest-python2-ubuntu18.04`

* Full tag alias: `1.12.0-python2.7.14-keras2.2.4-cpu-ubuntu18.04`
* Software: TensorFlow 1.12.0, Keras 2.2.4, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/tensorflow112_keras22_python27_mkl_notebook-190103](https://jetware.io/appliances/aise/tensorflow112_keras22_python27_mkl_notebook-190103?us=dockerhub)

#### `latest-python2-debian9`

* Full tag alias: `1.12.0-python2.7.14-keras2.2.4-cpu-debian9`
* Software: TensorFlow 1.12.0, Keras 2.2.4, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/tensorflow112_keras22_python27_mkl_notebook-190103](https://jetware.io/appliances/aise/tensorflow112_keras22_python27_mkl_notebook-190103?us=dockerhub)

#### `latest-python2-centos7`

* Full tag alias: `1.12.0-python2.7.14-keras2.2.4-cpu-centos7`
* Software: TensorFlow 1.12.0, Keras 2.2.4, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/tensorflow112_keras22_python27_mkl_notebook-190103](https://jetware.io/appliances/aise/tensorflow112_keras22_python27_mkl_notebook-190103?us=dockerhub)


### Issues

If you encountered a problem running this container, please file an [issue](https://github.com/jetware/dockerhub-tensorflow-notebook/issues).

---
(c) 2019 [Jetware](https://jetware.io)
