# VIT-MNIST
Trained Vision transformer from scratch on MNIST dataset. 28x28 MNSIT images were scaled to 196x196. 7x7 patches were fed to VIT. It has a depth of 4 with 8 multihead attention layers and the classification head attached to a dummy token (trainable) which was inserted along with the patches.<br>
The figure below shows the attention map of classification token the last year <br>
<img width="590" alt="image" src="https://github.com/Sachin-Bharadwaj/VIT-MNIST/assets/26499326/737f6882-c9ef-4b5b-a7fb-66555e3eedac">
Here are some of the examples from val set <br>

<img width="608" alt="image" src="https://github.com/Sachin-Bharadwaj/VIT-MNIST/assets/26499326/b6045604-6aec-42d8-8f10-5c445b4f81c9">

Have a look at learned positional embedding layer below. Note it does not show usual property that token nearby are close by (atleast it does not seem to be monotonic perfectly) <br>
<img width="428" alt="image" src="https://github.com/Sachin-Bharadwaj/VIT-MNIST/assets/26499326/72168fa2-9911-4f61-81af-9846c84bd4bc">

