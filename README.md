# Neural-Cellular-Automata-Image-Manipulation

This is the repository for both style transfer and CLIP text based image modification using deep neural cellular automata.
CLIP:\
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ieXiaoXfrcTt6f2vIGx3Fw1Oz3hyZm-Y?usp=sharing)

StyleTransfer:\
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1c7S7R52KjgNM3XrmADIRNKEFpEmgQONX?usp=sharing)

Artistic style transfer has been part of the quickly growing AI Art community in recent times. Pioneered by Gatys et al this class of methods allows for the transfer of a style, texture, pattern ect. to a target image. This has been made possible by the use of the expressive hidden features of large computer vision models like VGG19 to use as a loss function. The method by which this transformation is undertaken has come in many forms from the intial method which optimized the pixel of the image directly to newer forms that train some form of CNN to create a general style transfer network. The method presented in this paper is in the same vain as those newer methods but leveraging a new class of deep learning method, that of deep neural cellular automata. This new method brings with it the ability to transform any image to a target style, like the CNN method mentioned earlier, using the same automata update rule in an iterative fashion. This iterative fashion allows one to stop the process early for less stylization as well as resulting in video rather than a still image which, due to the dynamic nature of cellular automata, has visually pleasant properties. 

![alt text](./media/vgg_pasta.gif "VGG Style Transfer")


For more updates follow me on twitter [![Twitter Follow](https://img.shields.io/twitter/follow/AntonObukhov1?style=social&label=Subscribe!)](https://twitter.com/Omorfiamorphism)
