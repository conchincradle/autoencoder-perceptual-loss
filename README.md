# autoencoder_perceptual_loss

<div align=center><img src="https://user-images.githubusercontent.com/33627638/174434047-01c9e7df-22b4-4905-9c7f-4c88733c2911.jpg" width="150" height="150" />
<img src="https://user-images.githubusercontent.com/33627638/174434057-9f24356c-a47c-4fc9-b04e-8c674304d08a.jpg" width="150" height="150" />
</div>
<p align="center">dry&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  wet</p>

<p>Using the difference of the encoded latent vectors in the AutoEncoder, we could apply the condition into other images. </p>

- Below is the generated images with wet condition.
<div align=center><img src="https://user-images.githubusercontent.com/33627638/174434582-85f19dbf-654c-4bb5-8c0e-f79d334d8c19.jpg" width="150" height="150" />
<img src="https://user-images.githubusercontent.com/33627638/174434539-54f24c9d-8e06-42ef-95ca-ac1a4117d8bc.jpg" width="150" height="150" />
</div>
<p align="center">dry&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  wet</p>

<div align=center><img src="https://user-images.githubusercontent.com/33627638/174434083-50a58e4a-2a6c-4d6b-962a-714db887ff75.jpg" width="150" height="150" />
<img src="https://user-images.githubusercontent.com/33627638/174434092-a72c8586-d810-49e8-af53-e8e0450f16ce.jpg" width="150" height="150" />
</div>
<p align="center">dry&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp  wet</p>

- With different parameters

![image (4)](https://user-images.githubusercontent.com/33627638/174434623-de5dc366-d11a-44cc-97d1-b7f83a4a13c1.png)

- reverse condition

![image (3)](https://user-images.githubusercontent.com/33627638/174434631-3c7a54a2-b719-4308-b363-13bd9ad395f7.png)

- The same idea, using the transpanrency diffrence, apply it into the object
![image (5)](https://user-images.githubusercontent.com/33627638/174434735-004adb6c-fd73-4b52-a99b-68419b364999.png)

![image (6)](https://user-images.githubusercontent.com/33627638/174434864-b9e7b6ec-6085-4b4e-89cf-5059ee144705.png)

- Recently, I'm studying the LPIPS distance (A perceptual metric of image similarity) of the generated image.

<div align=center><img src="https://user-images.githubusercontent.com/33627638/174435068-7d909215-e765-483f-9001-6c4942932905.png" width="500" height="300" />
<img src="https://user-images.githubusercontent.com/33627638/174435038-2f0b699e-01d3-43a3-98c5-c1490f105aeb.png" width="300" height="300" />
</div>

- Fancy geenrated image

![8081d4f0-0f27-4eec-9776-a7dc5d5b77e3](https://user-images.githubusercontent.com/33627638/175891363-5d50806c-1f82-4237-a6db-54ae320e300e.jpg)



