# np-tensorflow

Course notes for a 4-day tensorflow for image and audio course

## Curated references:

- The book from Aurelien Geron. Check also the notebooks from his 
website [https://github.com/ageron/tf2_course](https://github.com/ageron/tf2_course). You can buy the book in Amazon. 

- The post by Andrej Karpathy on recurrent neural networks [http://karpathy.github.io/2015/05/21/rnn-effectiveness/](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

- Cristopher Olah's blog for a very crisp explanation on recurrent neural networks and computation graphs [http://colah.github.io/](http://colah.github.io/)

- Michael Nielsen's website [http://neuralnetworksanddeeplearning.com/](http://neuralnetworksanddeeplearning.com/)

**Note:** I do not recommend to follow any Medium.com publications/blogs, as the quality tends to be quite low. Most of them are downright wrong.

## For Audio

A popular way to use deep learning for audio classification is to extract spectrograms and then reduce the problem to an image classification task. 

- You can do this "on the fly", i.e., without having to create the spectrograms first [https://github.com/keunwoochoi/kapre](https://github.com/keunwoochoi/kapre)
- This is an older project using Tensorflow 1.0, also interesting [https://github.com/aqibsaeed/Urban-Sound-Classification](https://github.com/aqibsaeed/Urban-Sound-Classification)

For music generation, you can use e.g. ABC notation together with our character-level RNN.

