# SqueezeNet vs AlexNet: On the challenges of training condensed networks
_Original title: “Size isn’t everything, it’s what you (can) do with it that counts”: a comparison of SqueezeNet and AlexNet_

**analyses by:** Xavier Morin Duchesne  
**report by:** Xavier Morin Duchesne & Gordon Krieger  

We examine the deep learning neural network model SqueezeNet and compare its performance to a well-known neural network AlexNet. Improvement in deep learning networks
sometimes comes at the expense of size; increasing the depth or width of a network can often give an increase in performance. SqueezeNet is an attempt to move in the other direction: produce a small network that optimizes for size, while keeping an acceptable baseline accuracy. We confirm the main claim of the paper of having
AlexNet-level accuracy, but report difficulties training the model. We observe that starting from a pre-trained model (readily available online) is much easier than training it from nothing. Additionally, if one must train it from scratch, our ablation subexperiments on SqueezeNet's architecture show that adding a batch normalization layers to SqueezeNet's Fire module gives a measurable increase in learning rate well worth the added parameters for the batch layers. Ultimately, the ideas proposed by SqueezeNet, that more can be achieved with less, are very interesting so long as one is able to achieve the desired level of performance.
