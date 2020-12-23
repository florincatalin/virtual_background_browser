# virtual_background_browser
Virtual Background, Segmentation, Tensorflow, BodyPix, WebRTC, mediaRecorder, webm

Numerous examples of the use of machine learning have emerged recently. An example would be that of virtual backgrounds, using 
BodyPix, Real-time Person Segmentation in the Browser with TensorFlow.js.

https://blog.tensorflow.org/2019/11/updated-bodypix-2.html

In addition to creating the virtual background in the browser, I also tried to make a recording of the respective video sequence, using the documentation and examples from WebRTC.

https://webrtc.github.io/samples/

This project is inspired by:

https://github.com/bensonruan/Selfie-Anywhere

https://bensonruan.com/selfie-anywhere-person-segmentation-with-bodypix/

This project includes codes from the following repositories:

https://www.tensorflow.org/js/

https://github.com/tensorflow/tfjs

https://github.com/tensorflow/tfjs-models

Apache-2.0 License 

NOKUBI Takatsugu

https://github.com/knok/virtbg

http://blog.daionet.gr.jp/knok-e/2020/05/10/virtual-background-using-webcam/

Apache-2.0 License

WebRTC:

https://webrtc.github.io/samples/

https://github.com/webrtc/samples

BSD-style license


Background image is from Pixabay 

https://pixabay.com/users/yeskay1211-6332528/

License Free for commercial use

No attribution required

Author Yeskay1211

See a demo:

![](https://github.com/florincatalin/virtual_background_browser/blob/main/virtual_background_demo_short.gif)



Tested with Firefox 82.0.

Useful information I found on MDN web docs:

https://developer.mozilla.org/en-US/docs/Web/API/MediaStream_Recording_API

What driver do you use for your intel gpu?

You can force hardware acceleration in **Firefox** - WebRenderer in **about:config** by setting:

  `gfx.webrender.all - true`
  
  `gfx.webrender.enabled - true`
  
--> restart browser and

  `layers.acceleration.force-enabled - true`
  
--> restart browser

Then check in **about:support** that you have instead Compositing: Basic, Compositing: WebRenderer and also WebGL 2 support.

Note: depending of your driver/gpu you may not have WebGL 2 support.

**If you do not have WebGL enabled the application will run very slowly!**
