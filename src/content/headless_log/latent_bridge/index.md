---
title: "Latent_bridge"
date: 2022-01-26T19:22:52+01:00
draft: false
---

{{< img src="media/vae_train.jpg" alt="a rotating cloud of tiny painted portraits on black background" caption="A dataset generated with Processing">}}

{{< img src="media/vae_gen.jpg" alt="a rotating cloud of tiny painted portraits on black background" caption="A dataset generated with a neural network" >}}

While I was trying out a different network architecture I quickly needed a new dataset. Instead of downloading one I manually generated images with Processing and used them to train this network. The second image shows the whole latent space of this generator, What's interesting is that it is able to fill in the gaps of the randomly generated data, thus generate smooth transitions between images of the original dataset.