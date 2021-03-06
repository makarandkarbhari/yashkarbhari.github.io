---
layout: page
title: Software, data and code
description: Scripts, software and material for replication
---

<section>
<section class="spotlight">
	        <div class="image"><img src="/assets/images/captcha2.png" alt="" /></div>
		<div class="content">
			<header class="major">
			<h2 align="center">Word Segmentation using Tensorflow and OpenCV</h2>
			</header>

<p> The dataset was taken from a Kaggle competition, and has had around 1000 reCAPTCHA images to train on. I have used two different approaches to solve this problem:</p>
	
<p>1) Using OpenCV and creating bounding box for the image using hard-coded dimensions for the bounding boxes as the reCAPTCHA images in the dataset had the letters at the same place for every image.</p>

<p>2) Using TensorFlow, I fine tuned the model to achieve 93% test accuracy. I preprocessed the data by normalizing, resizing and splitting, and then built the model with Conv, BatchNorm, MaxPooling Layers.</p>		
<p class="icon fa-star"> <a href="https://github.com/yashkarbhari/Word-Segmentation-using-OpenCV">Link</a></p>
	</div>
	

</section>
