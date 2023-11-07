# Fall-Detection-with-Federated-Transfer-Learning
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
<a target="_blank" href="https://colab.research.google.com/github/moshiurtonmoy/Fall-Detection-with-Federated-Transfer-Learning/blob/master/main.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

A classic implementation of Federated Learning (FedAvg) for identifying `FALL` and `ADL` from images utilizing Transfer Learning Tensorflow and Numpy.
* VGG16 as Feature Extractor
* Federated Averaging
<hr/>

**Data Source** - <a href='http://fenix.ur.edu.pl/~mkepski/ds/uf.html'>UR Fall Detection Dataset</a> <br/>
The dataset contains 70 videos illustrating `FALL` and `ADL` events. We've extracted RGB frames from the videos for this work and augmented the dataset by employig common augmentation techiniques (e.g. rotation, flipping, etc.). <br>
<br/>
![sample_data](https://github.com/moshiurtonmoy/Fall-Detection-with-Federated-Transfer-Learning/blob/master/sample.png)
