# subtitles
subtitles for bash scripting assignment

## Challenge Instructions
Write modular shell scripts that automate the subtitles in different files. Clone this repository which contains 3 subtitles files develop a script that gives the [following](#Output) output in single file.

## Output
output.txt

In this lesson, we'll cover the basics of the Intel distribution of OpenVINO toolkit, different computer vision model types, the available pre-trained models in the software, choosing the right pre-trained model for your app, and loading and deploying a basic application with the pre-trained model.

Let's kick things off with a brief introduction to the Intel distribution of OpenVINO toolkit. The OpenVINO toolkit name comes from
open visual inferencing and neural network optimization, not wine. As the name implies, it is largely focused around optimizing neural network inference and it's open source. It's developed by Intel and help support fast inference across Intel CPUs, GPUs, FPGAs, and the Neural Compute Stick with a common API. You can take models built with multiple different frameworks, like TensorFlow or Caffe, and use its model optimizer to optimize for inference. Once a model is put through the model optimizer, you can use it with the inference engine, which helps speed inference on the related hardware. There's also a wide variety of pre-trained models already put through the model optimizer, which we'll cover in this lesson as well as those later lessons for the other components. So how does this relate to AI at the Edge? By optimizing for model speed and size, this software enables running at the Edge. Note that this does not mean an increase in inference accuracy. This needs to be done in training beforehand. The smaller, quicker models the software generates, along with the hardware optimizations it provides, are great for lower resource applications. An Internet of things device, for instance, doesn't have the benefit of the Cloud where it might have multiple GPUs and almost unlimited memory space to run its applications.

As mention before, there are a lot of pre-trained models available directly in the software. Let's take a quick look at what pre-trained models are and how they are used. Pre-trained models referred to models where retraining has already occurred. This can lead to high even cutting-edge accuracy and avoids the need for large-scale data collection and long costly training. Given knowledge of how to preprocess inputs and handle the outputs, you can plug these directly into your own app. In the toolkit, pre-trained models refers specifically to the Model Zoo containing pre-trained models already converted using the model optimizer. As such, you can use these models directly with the inference engine. You seen this slide before, but here's just a quick visual reminder on how you can feed the pre-trained model directly into the inference engine. Before we get into the full set of pre-trained models available in the OpenVINO toolkit, let's cover some of the basics of computer vision models first.
