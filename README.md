## Contents
* [Supervised Learning](https://github.com/zhedongzheng/finch#supervised-learning)
* [Deep Learning](https://github.com/zhedongzheng/finch#deep-learning)
* [Computer Vision](https://github.com/zhedongzheng/finch#computer-vision)
* [Natural Language Processing](https://github.com/zhedongzheng/finch#natural-language-processing)
* [Computational Framework](https://github.com/zhedongzheng/finch#computational-framework)
## Supervised Learning
* Logistic Regression
    * Logistic Regression &nbsp; | &nbsp; Java &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/java-models/LogisticRegression.java) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/java-models/LogisticRegressionTest.java)
* [Support Vector Machine](https://zhedongzheng.github.io/finch/svm)
    * Linear SVM Classifier &nbsp; | &nbsp; Java &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/java-models/LinearSVM.java) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/java-models/LinearSVMTest.java)
    * Linear SVM Classifier &nbsp; | &nbsp; TensorFlow &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/linear_svm_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/linear_svm_clf_test.py)
## Deep Learning
* Neural Network / Multilayer Perceptron
    * MLP Classifier &nbsp; | &nbsp; TensorFlow &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/mlp_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/mlp_clf_test.py)
    * MLP Classifier &nbsp; | &nbsp; PyTorch &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/torch-models/mlp_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/torch-models/mlp_clf_test.py)
* Autoencoder
    * Stacked &nbsp; | &nbsp; TensorFlow &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/autoencoder.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/autoencoder_test.py)
* [Convolutional Neural Network](https://zhedongzheng.github.io/finch/conv)
    * CNN Classifier &nbsp; | &nbsp; TensorFlow &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/conv_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/conv_clf_test.py)
    * CNN Classifier &nbsp; | &nbsp; PyTorch &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/torch-models/cnn_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/torch-models/cnn_clf_test.py)
* [Recurrent Neural Network](https://zhedongzheng.github.io/finch/rnn)
    * TensorFlow  
       * RNN Classifier &nbsp; | &nbsp; TensorFlow &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn_clf_test.py)
       * RNN Regressor &nbsp; | &nbsp; TensorFlow &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn_regr.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn_regr_test.py) &nbsp; | &nbsp; [Visualization](https://github.com/zhedongzheng/finch/blob/master/assets/rnn_regr_plot.gif)
       * RNN Language Model &nbsp; | &nbsp; TensorFlow &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn_lang_model.py) &nbsp; | &nbsp; [Shakespeare Text Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn_shakespeare_test.py)
    * PyTorch
        * RNN Classifier &nbsp; | &nbsp; PyTorch &nbsp; | &nbsp; [OOP Model](https://github.com/zhedongzheng/finch/blob/master/torch-models/rnn_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/torch-models/rnn_clf_test.py)
## Computer Vision
* OpenCV
    * Basic Operations
        * [Resize](https://github.com/zhedongzheng/finch/blob/master/computer-vision/resize.ipynb)
        * [Rotations](https://github.com/zhedongzheng/finch/blob/master/computer-vision/rotations.ipynb)
    * Image Segmentation
        * [Contours](https://github.com/zhedongzheng/finch/blob/master/computer-vision/contours.ipynb)
        * [Sorting Contours](https://github.com/zhedongzheng/finch/blob/master/computer-vision/sorting-contours.ipynb)
    * Detection
        * [Face & Eye Detection](https://github.com/zhedongzheng/finch/blob/master/computer-vision/face-eye-detection.ipynb)
        * [Walker & Car Detection](https://github.com/zhedongzheng/finch/blob/master/computer-vision/car-walker-detection.ipynb)
## Natural Language Processing
* Language Processing in Python
   * [Preprocessing](https://github.com/zhedongzheng/finch/blob/master/natural-language-processing/text-preprocessing.ipynb)
   * [Embedding](https://github.com/zhedongzheng/finch/blob/master/natural-language-processing/char-embedding.ipynb)
## Computational Framework
* NumPy
   * Useful Ops in ML
      * [np.roll](https://github.com/zhedongzheng/finch/blob/master/numpy-basic-ops/np.roll.ipynb) shifts array elements along given axis
      * [np.resize](https://github.com/zhedongzheng/finch/blob/master/numpy-basic-ops/np.resize.ipynb) returns a new array with a specified shape
* TensorFlow
   * Useful Ops in ML
      * [feed_dict](https://github.com/zhedongzheng/finch/blob/master/tensorflow-basic-ops/feed_dict.ipynb) also be used to update an existing node in graph
      * [tf.concat &nbsp; | &nbsp; tf.stack](https://github.com/zhedongzheng/finch/blob/master/tensorflow-basic-ops/tf.concat%20%26%20tf.stack.ipynb) concatenates a list of tensors into a large tensor
      * [tf.unstack &nbsp; | &nbsp; tf.split](https://github.com/zhedongzheng/finch/blob/master/tensorflow-basic-ops/tf.unstack%20%26%20tf.split.ipynb) splits a tensor into a list of sub-tensors
      * [tf.squeeze](https://github.com/zhedongzheng/finch/blob/master/tensorflow-basic-ops/tf.squeeze.ipynb) removes 1 in the shape of tensor
      * [tf.nn.embedding_lookup](https://github.com/zhedongzheng/finch/blob/master/tensorflow-basic-ops/tf.nn.embedding_lookup.ipynb) represents each word index by a vector
