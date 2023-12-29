# colorization-with-Conditional-GAN
It is a project that implement colorization with UNet and Resnet34
# Dataset
We download 10000 image from COCO dataset. 8000 for training. 2000 for validation
# Method
We pretrain a resnet34-unet as the backbone of generator.   
The final.pt saves the model that was trained for 20 epochs.  
The final_v2.pt saves the model that was trained for 40 epochs.  
The final_v3.pt saves the model that was trained for 60 epochs.  
## step:
1. define Generator
2. define Discriminator
3. define loss function
4. construct model
5. training
6. save output image
# anothor method
Using Res34 generator  
Use the same Discriminator and loss function 
## step:
1. pretrain the model Using Res34 generator
2. save output image
3. compress the model to zip file
