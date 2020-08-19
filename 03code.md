---
layout: page
title: Software, data and code
description: Scripts, software and material for replication
---

<section>
  
<h3>Word Segmentation using TensorFlow and OpenCV</h3>

<div class="box alt">
	<div class="row uniform 100%">
	<div class="8u">
	<p align="justify">
<p class = "icon fa-circle"> The dataset was taken from a Kaggle competition, and has had around 1000 reCAPTCHA images to train on. I have used two different approaches to solve this problem.</p>
<p class = "icon fa-circle"> 1) Using OpenCV and creating bounding box for the image using hard-coded dimensions for the bounding boxes as the reCAPTCHA images in the dataset had the letters at the same place for every image.</p>
		
<p class = "icon fa-circle">2) Using TensorFlow, I fine tuned the model to achieve 93% test accuracy. I preprocessed the data by normalizing, resizing and splitting, and then built the model with Conv, BatchNorm, MaxPooling Layers.</p>
		</p>
<p class="icon fa-star"> <a href="https://github.com/yashkarbhari/Word-Segmentation-using-OpenCV">Link</a></p>
	</div>
<div class="4u">
	<span class="image fit"><img src="assets/images/captcha.png" alt="" /></span>
	</div>
	</div>
	</div>
</section>
