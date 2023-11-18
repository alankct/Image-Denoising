# Image-Denoising
_How can we use neural networks to denoise images?_

_Furthermore, how good are the U-Net and Autoencoder models at denoising images?_

<p align="center">
  <img width="579" alt="Screenshot 2023-11-12 at 12 15 35 PM" src="https://github.com/alankct/Image-Denoising/assets/86837040/013f4900-aa63-4a56-b400-1d711a2787b1)">
</p>

>  Image noise is random variations of brightness or colors in images. Noise can be caused by a number of factors, like: poor lighting conditions, a high ISO (a camera's sensitivity to light), long exposure times, heat, and more.

<h5> 
  In this study, Alex and I tested the U-Net and Autoencoder models for Image Denoising—a task in computer vision problem that seeks to remove noise from an image in order to yield a cleaner result. 
</h5>

We implemented our own U-Net and Autoencoder models (**our code can be found in image-denoising.ipynb**), and compared them qualitatively and quantitatively: we used the MNIST dataset to evaluate the denoising performance for both networks. Our results can be found in our report: **Image_Denoising.pdf**

> The architecture implementations are laid out in the report, as well as the rationale behind them

<p align="center">
  Testing the models' ability to remove noise using different noise levels inputs
</p>
<p align="center">
  <img width="579" alt="Screenshot 2023-11-12 at 12 15 35 PM" src="https://github.com/alankct/Image-Denoising/assets/86837040/927b92f1-968f-4a1e-8f1f-b5011e3e58ab">
</p>

> The report lays insights on what the most effective/efficient strategies are for this task

<p align="center">
  Quantitatively measuring both models' performances on denoising images
</p>
<p align="center">
  <img width="516" alt="Screenshot 2023-11-12 at 12 14 39 PM" src="https://github.com/alankct/Image-Denoising/assets/86837040/91b2041a-6cda-4f26-b80f-65b22acef031">
</p>
