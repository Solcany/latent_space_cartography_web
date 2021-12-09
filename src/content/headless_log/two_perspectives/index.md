---
title: "two perspectives"
date: 2021-12-08T21:04:08+01:00
draft: false
---

Two different perspectives on 1000 images created by a generator trained on painted portraits dataset. The first has the images clustered by their visual similarity. The second clusters the respective latent points - that is the seeds that the generator interpreted as the images. I was expecting that similar latent points would also produce visually similar images but this isn't the case.

{{< video src="media/imgs_output" alt="a rotating cloud of tiny painted portraits on black background" autoplay="true" 
muted="true" loop="true" controls="false" >}}

Clustering by visual similarity

{{< video src="media/vectors_output" alt="a rotating cloud of tiny painted portraits on black background" autoplay="true" muted="true" loop="true" controls="false" >}}

Clustering by latent points similarity