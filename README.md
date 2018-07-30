![las2peer](https://rwth-acis.github.io/las2peer/logo/vector/las2peer-logo.svg)

# las2peer-TensorFlow-TextToText-Service
[![Build Status](https://travis-ci.org/rwth-acis/las2peer-TensorFlow-TextToText-Service.svg?branch=master)](https://travis-ci.org/rwth-acis/las2peer-TensorFlow-TextToText-Service) [![codecov](https://codecov.io/gh/rwth-acis/las2peer-TensorFlow-TextToText-Service/branch/master/graph/badge.svg)](https://codecov.io/gh/rwth-acis/las2peer-TensorFlow-TextToText-Service) 

This las2peer service is a wrapper for a customized version of the [nmt chatbot](https://github.com/daniel-kukiela/nmt-chatbot). It based on the [nmt](https://github.com/tensorflow/nmt) repository. In the scope of the Social Bot Framework this service is used to generate text, but it can also be used for text translation.
The service implements the [BotContentGenerator interface](https://github.com/rwth-acis/las2peer/blob/master/core/src/main/java/i5/las2peer/logging/bot/BotContentGenerator.java). 

Build
--------
Execute the following command on your shell:

```shell
ant all 
```

Start
--------

To start the data-processing service, use one of the available start scripts:

Windows:

```shell
bin/start_network.bat
```

Unix/Mac:
```shell
bin/start_network.sh
```
