# Brain-Tumor-Segmentation

<ul>
  <li>U-Net model has a “U” shape. The architecture is symmetric and consists of two major parts - the left part is called contracting path also called encoder, the right part is expansive path also known as decoder.</li>
<li>U-net is very powerful model for Image segmentation in bio medical analysis. Additional power for U-Net to up-sample and down-sample helps it to perform even more better than the regular U-Net.</li>
</ul>

<img href="unet+inception.png"/>

<ul>
  <li>The image in the figure demonstrates the architecture of our model. 
</li>
  <li>
We additionally added Inception at every step of up sampling and down sampling the given image.</li>
  <li>
This provided the boost in performance of U-Net and reduced the computational cost.</li>
  </ul>
