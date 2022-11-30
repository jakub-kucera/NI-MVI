I didnt really look into discussion about this Kaggle chalenge nor anybody elses solution, since then I would make a solution too similar to someone else, even thought I would try otherwise. Plus I also would have not learned as much.
So, first I just kind of started blindly implementing a basic GAN without any thinking, which is where the implementation is now.

When I started researching I came across multiple articles, one of which was this one, which might be actually a bit too similar to my task, which is kind of what I tried to prevent, but too late for that. 
Since this article talks directly about using Cycle GANs to transform real images into artworks in some specified art style.
In this article, it was said that a basic GAN for this use case would work poorly mainly because of a loss function between a real Monet style paintings and fake ones. 
Because of that I will change my GAN implementation into a CycleGAN.  

https://towardsdatascience.com/transforming-real-photos-into-master-artworks-with-gans-7b859a43e6ea

If this will seem too easy for me and not take that much time, I am also considering upgrading my implementation to a Conditional CycleGAN, which could for example allow me to convert images into multiple art styles, depending on what is specified in a query.

https://arxiv.org/abs/1611.07004

https://machinelearningmastery.com/how-to-develop-a-pix2pix-gan-for-image-to-image-translation/
