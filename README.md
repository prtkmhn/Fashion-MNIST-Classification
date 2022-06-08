# Fashion-MNIST-Classification
A neural network and deep learning project to create a custom model that follows the given requirements. The model consists of a Stem which takes an image and divides it into 4 patches of 14x14. Each patch is then vectorized and transformed to the feature vector. Next a linear layer is used which then is passed to the backbone. The Backbone consists of 2 blocks which then consists of 2 multi-layer perceptron (MLP). Each MLP first has a non-activation function, in this case the ReLU function is used. Following that, LeakyReLU function is used. The output is then passed onto the Classifier. The final model accuracy is 88.09%.

To run this, use Google Colab or Jupyter Notebook

&nbsp;
![thumbnail](https://user-images.githubusercontent.com/70578823/172704986-ac4a02dd-db38-4000-a3be-1cd93ee65b42.png)
&nbsp;

&nbsp;
![overview](https://user-images.githubusercontent.com/70578823/172705211-ef5ff904-407b-40f0-95dc-83e8a6483b61.png)
&nbsp;


&nbsp;
![backbone](https://user-images.githubusercontent.com/70578823/172705267-a55202bb-a938-4b81-b1e8-14a1b6780eaa.png)
&nbsp;

&nbsp;
![stem](https://user-images.githubusercontent.com/70578823/172705288-1994b2fa-83d6-4bbe-99eb-67315cd7543a.png)
&nbsp;

&nbsp;
![classifier](https://user-images.githubusercontent.com/70578823/172705320-11ba545f-7fe2-477f-b62c-4018267b6609.png)
&nbsp;

&nbsp;
![result](https://user-images.githubusercontent.com/70578823/172705360-2ddf05e3-5f2d-4cc4-a8fe-b69c024ecf89.png)
&nbsp;

