# Tobias Lange - Hack-a-thing-2

## Short description of what you attempted to build
I set out to learn as much about Pysyft as I possibly could. However, when I went to Pysyft tutorials, there was a disclaimer that I should spend some time with Pytorch beforehand. As a result, I spent a few hours understanding the basic syntax of Pytorch and learned how to build a simple neural network for an MNIST dataset (similar to what I did in Hack-a-Thing-1 in a different language). However, when I was making my final push I somehow pushed to my first hack a thing and had to submit a sort of pull request that caused me to lose my work permamantly :( I followed a few tutorials on the Pytorch website to build out my basic framework and model.

Once I had completed enough Pytorch such that I felt comfortable moving over to Pysyft, I went on openminded to learn how to download Pysyft and begin my tutorial. I followed the directions to a tee, making sure I had the exact version of Pytorch needed, the right python, and used "pip install syft" to pull in all libraries. This went swimmingly, but when I ran some test code to ensure syft had been properly installed, I got an error. I panicked slightly, since I knew I had done everything right, so I re-did the steps, tried to download it through conda, where I got some errors, and then following a couple more install sequences to see if any would work. This took me quite some time, and every time I still got the same error. I dug deeper into the error message and realized it was a Darwin (MacOS kernel) related error. I then realized I needed to upgrade my MacOS from 10.13 to 10.15. Unfortuantely, this required 20GB of space, and my computer has ~1.5 GB at the moment. I then went about aggressively reviewing apps/files to figure out how to free up enough space for me to upgrade my MacOS. I unfortuantely spent 2-3 hours in this whole step of originally trying to download PySyft to upgrading my MacOS, meaning I had less time to work on PySyft. Even after I did this update, it did not work for me - I got a gcc error, which I was very confused about. I spent a couple more hours (bringing my enviornment setup to 4-5 hours) trying to figure out what went wrong. Ultimately, I conferred with my housemates (Jake and Matt), and they let me use their server to work in PySyft, which ended up being a success.

Once I had properly installed Pysyft, I spent some time reviewing the theory of federated learning (https://arxiv.org/pdf/1811.04017.pdf) was reccomended on openminded's git). As I stated in the first hack-a-thing, I felt like I jumped in too quickly without taking the requisite time to truly understand what I was doing. This time, I didn't make the same mistake.

I then followed the first 5 tutorials on openminded's github page, learning how to run ML models from different virtual workers, and the PySyft syntax in general. I learned how to build a basic model.

## Who did what (if you worked with someone else)
I worked alone - I felt that I would get more out of the exercise if all the code was produced by myself.

## What you learned

I learned basic PyTorch syntax, how to build a MNIST classifier (so sad that I lost it!), and how to use Pysyft. I felt very excited understanding the toby/julie example - how these things work together is exceptionally exciting and how tensors point to virtualworkers etc...

## How does this hack-a-thing inspire you or relate to your possible project ideas?
I had done my first hack-a-thing on simple Tensorflow, with the intent of learning TensorFlow Federated for my second hack-a-thing since we had decided our group very early. Recently, Matt Kenney realized that TensorFlow Federated was not shippable, and that we needed a different library to run federated learning. As a result, learning TensorFlow Federated was a waste of time, so I instead went with another language that we thought could be applicable - PySyft, an open-source language. This language will be used to run federated learning on devices, so it is essential I understand how it works.

## What didn’t work
My git skills are lacking, as well as my abilities to set up my dev enviornment. This caused me a lot of grief and grey hairs, because I didn't have enough time to really learn PySyft since I spent so much of my time with git and dev enviornment. I also lost my file when I did a git pull somehow, and I know that I really need to get stronger skills with git.
