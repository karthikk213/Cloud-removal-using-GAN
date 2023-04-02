# Cloud-removal-using-GAN

##Introduction
Detecting and Observing Earth's surface is needed in the
modern world for various applications. It starts from
national defence security, research activities and weather
monitoring, and many more, we need surveillance to capture
the required area on earth. Remote sensing is the process to
capture and monitor the earth's surface images. Satellite
captures the earth's surface through various wavelength
bands. Unfortunately, opaque clouds covered the earth's
surface, which hides the details of the image. The types of
clouds play a major role in images. They are thick, thin, and
shadow clouds.The atmosphere affects the quality of the
satellite imagery.Cloud removal in satellite images plays an
important role in not only getting more information but
enhancing the spectral variation in the images. Our research
study covers the approach of removing thin clouds from a
single optical remote-sensing image.

## concept behind GAN
![s_84D9D849F786EC83B26BF2A0F74F0C33230682E8BA1D41AD8C3F3D770D23236A_1566172128772_gan](https://user-images.githubusercontent.com/113841890/228699301-fa7a2c65-7f19-4c56-a83c-513c724da262.png)

## General Structure of GAN
![image-1582299090634-df900b01178a9a4c10f96028ae03f354](https://user-images.githubusercontent.com/113841890/229361411-e43f2fee-f799-4e68-8c85-35e342cef3bd.png)


## Generator structure
![Strcuture of generator](https://user-images.githubusercontent.com/113841890/229360612-4e45bf3f-7a8e-476a-8b40-b4313f3a988f.PNG)

## Residual Block
![Residual block](https://user-images.githubusercontent.com/113841890/228701819-46f47b99-54c3-4964-8a88-1468d4a4e767.PNG)


## Spatial Attentive Blocks
![Spatial Attentive Block](https://user-images.githubusercontent.com/113841890/228701847-cfc2ccde-375a-4609-885e-0a1f5e5e57a3.PNG)


## Spatial Attentive Module
![Spatial Attentive Module](https://user-images.githubusercontent.com/113841890/228701871-a6e83b5f-f8f0-4785-aaf4-ee35946efecb.PNG)

## Discriminator
![discriminator](https://user-images.githubusercontent.com/113841890/228702016-39bbc653-6cba-47e6-a053-0da507da6851.PNG)

## Epoch graphs - 1500 epochs
![loss_graph_001500](https://user-images.githubusercontent.com/113841890/229360663-760d26f4-052d-4bf3-87fb-fa1c181c20d5.jpg)

#### Around 900 epochs, we have less generator loss, so we can use the model000900.h5 to predict the cloudless image.

#### This project is not yet completed Fully, as further studied and modifications needed to be done, Some resulting images are not upto the level.




