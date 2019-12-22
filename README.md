# image_pyramid
<h1> Gaussian And Laplacian Image Pyramids </h1>
This is an implementation of Gaussian and Laplacian Image Pyramids from coded up from Scratch. 

<p> To run this, place the image you wish to run the Algorithm inside "seed_images", and in the Notebook set the variable "imageName" to that file. </p>

<p> An image pyramid is a multiscale representation of an image. This is achieved by repeatedly smoothing and subsampling the image in order to achieve the desired resolution </p>
<p align="center">
<img src = "https://en.wikipedia.org/wiki/Pyramid_(image_processing)#/media/File:Image_pyramid.svg"/ alt="image pyramid">
</p>
<h3> Sample Input: </h3>

<p align="center">
  <img src="seed_images/messi.jpg"/>
</p>


<h3> Results: Gaussian Pyramid </h4>

<h5> Level 1 </h5>
<p align="center">
  <img src="results/messi_results/gaussian_pyramid/messi_gaussian_level_0.jpg"/>
</p>


<h5> Level 2 </h5>
<p align="center">
  <img src="results/messi_results/gaussian_pyramid/messi_gaussian_level_1.jpg"/>
</p>


<h5> Level 3 </h5>
<p align="center">
  <img src="results/messi_results/gaussian_pyramid/messi_gaussian_level_2.jpg"/>
</p>


<h5> Level 4 </h5>
<p align="center">
  <img src="results/messi_results/gaussian_pyramid/messi_gaussian_level_3.jpg"/>
</p>

<h3> Results: Laplacian of Gaussian Pyramid </h4>

<h5> Level 1 </h5>
<p align="center">
  <img src="results/messi_results/log_pyramid/messi_log_level_0.jpg"/>
</p>


<h5> Level 2 </h5>
<p align="center">
  <img src="results/messi_results/log_pyramid/messi_log_level_1.jpg"/>
</p>


<h5> Level 3 </h5>
<p align="center">
  <img src="results/messi_results/log_pyramid/messi_log_level_2.jpg"/>
</p>


<h5> Level 4 </h5>
<p align="center">
  <img src="results/messi_results/log_pyramid/messi_log_level_3.jpg"/>
</p>


<h3> Results: Difference of Gaussian Pyramid </h4>

<h5> Level 1 </h5>
<p align="center">
  <img src="results/messi_results/laplacian_pyramid/messi_laplacian_level_0.jpg"/>
</p>

<h5> Level 2 </h5>
<p align="center">
  <img src="results/messi_results/laplacian_pyramid/messi_laplacian_level_1.jpg"/>
</p>

<h5> Level 3 </h5>
<p align="center">
  <img src="results/messi_results/laplacian_pyramid/messi_laplacian_level_2.jpg"/>
</p>

<h5> Level 4 </h5>
<p align="center">
  <img src="results/messi_results/laplacian_pyramid/messi_laplacian_level_3.jpg"/>
</p>
<br/><br/>
<b><p> PS: Increase Brightness for better visibility of results </p> </b>

<p> You can read more about Image Pyramids <a href="https://en.wikipedia.org/wiki/Pyramid_(image_processing)"> here</a>.</p>
<p> You can read more about Gaussian Filters <a href="https://en.wikipedia.org/wiki/Gaussian_filter"> here</a>.</p>
<p> You can read more about Laplacian and other Edge filters <a href="http://www.aishack.in/tutorials/sobel-laplacian-edge-detectors/"> here</a>.</p>


