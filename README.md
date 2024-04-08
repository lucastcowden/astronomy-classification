For this project, I utilize a simple dense, or fully connected layer, for my neural networks. When making this project I wanted 
to explain for readers why we choose specific functions (such as NLL loss, or sigmoid vs. softmax) for our model. Therefore, I
took time to write out the equations and reasonings at each step. Not only do I think this will help viewers understand the
underlying thought process, but it also reinforced these ideas in my own head, helping me keep these ideas in mind when creating
more classification projects going forward. I learned a lot while making this project, especially in terms of how binary
classification differs from multiclass classification. One important thing to note is that the data we use for both models is
composed of 0 and 1 labels, meaning that our second model will not see any quasars. I actually mention this in the notebook,
but I thought I would emphasize this here. However, if our model did see data with 3 labels, it would be able to perform on this 
data as well.
