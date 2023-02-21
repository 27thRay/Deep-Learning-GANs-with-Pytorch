# Deep-Learning-GANs-with-Pytorch
Deep Learning GANs on CIFAR-100 Dataset using Pytorch
1. Deep Convolutional GAN
FID Score of 68.26
IS Score of 4.727
Images overall still slightly blurry
![image](https://user-images.githubusercontent.com/100133474/220403132-1f4d8614-ea9c-45c8-acc6-bb77b5edcbfc.png)


2. Wasserstein GAN - Experiment Failed
FID Score of 495
IS Score of 1.0
WGAN Experiment Failed
![image](https://user-images.githubusercontent.com/100133474/220403096-e25a68b1-bda7-4725-b0eb-ee08bf1eb785.png)


3. Conditional GAN
FID Score of 241.65
IS Score of 2.39
Images still of poorer quality than DCGAN
![image](https://user-images.githubusercontent.com/100133474/220403063-6e788185-664b-4559-ae7c-e8e3e9076be8.png)


4. Auxillary Classifier GAN
FID Score of 148.64
IS Score of 2.78
Images improved and are of better quality than CGAN but still poorer than DCGAN
![image](https://user-images.githubusercontent.com/100133474/220403029-813e0e77-c21f-4831-80d6-bcc5f7751794.png)


5. Auxillary Classifier with BIGGAN Elements
FID Score of 102.98
IS Score of 3.24
Images improved and are of better quality than CGAN & ACGAN but still poorer than DCGAN
![image](https://user-images.githubusercontent.com/100133474/220402963-496d1bc5-472c-463e-87a9-649bf8acecf6.png)


6. BIGGAN
FID Score of 51.51
IS Score of 6.74
Images improved and are of better quality than CGAN & ACGAN and even DCGAN thus it is the final best model.
![image](https://user-images.githubusercontent.com/100133474/220402925-ef750dec-463d-4f95-9c99-f3111a288b11.png)


Final Images from BIGGAN:


![image](https://user-images.githubusercontent.com/100133474/220402836-982850e2-bd02-43d0-a08e-a08030065ae8.png)


All Runs are recorded in WandB:
https://wandb.ai/raymondng009/DEEL-CA2-GAN/table?workspace=user-
<img width="959" alt="image" src="https://user-images.githubusercontent.com/100133474/220396149-3b717d14-5056-49ff-b9c7-5c6d60825b95.png">
