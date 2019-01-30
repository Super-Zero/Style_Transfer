# Style Transfer
Transfer the style of an image to another image using Convolutional Neural Networks (CNNs) with PyTorch.

The model uses a pre-trained Net, the VGG19 Net, to extract the features of the content and style images to come up with a new design image. The style transfer method was created by Leon A Gatys in this paper https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf

You can run it on Google Collaboration and take advantage of the GPU's power to process the style transfer since it involves intense computational operations. Here is the link: https://colab.research.google.com/drive/1_uwsL0AA1O8z9pyrT8ZIB3CekTE5DCxP


The below image shows on the left the content or target image and on the right the style image that is going to be transferred to the target image.


<img src="images/Content-Style.jpg">



The below image shows the before and after results of the style transfer.
<img src="images/before-after.jpg">
