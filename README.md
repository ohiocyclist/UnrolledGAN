# UnrolledGAN
The Unrolling trick to prevent mode collapse ( https://jonathan-hui.medium.com/gan-unrolled-gan-how-to-reduce-mode-collapse-af5f2f7b51cd ) is very useful, but I saw a gap in Tensorflow 2.0 code for it, so I built it in to the Tensorflow sample DCGAN code.  It's only about 15 new lines, in the generator loss and training functions.
