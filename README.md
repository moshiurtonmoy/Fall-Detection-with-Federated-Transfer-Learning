# Fall-Detection-with-Federated-Transfer-Learning
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
<a target="_blank" href="https://colab.research.google.com/github/moshiurtonmoy/Fall-Detection-with-Federated-Transfer-Learning/blob/master/main.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  [![DOI:10.1007/978-981-99-8937-9_64](https://zenodo.org/badge/DOI/10.1007/978-981-99-8937-9_64.svg)](https://doi.org/10.1007/978-981-99-8937-9_64) 
</a>

Leveraging Federated Learning and Transfer Learning for identifying `FALL` and `ADL` from images. We have employed:
* Feature Extractor: `VGG16`
* Aggregation Technique: `FedAvg`

This work has been published as a conference proceedings in BIM 2023, titled <a href='https://doi.org/10.1007/978-981-99-8937-9_64'>Federated Transfer Learning for Vision-Based Fall Detection.</a>
<hr/>

## Dataset
<a href='http://fenix.ur.edu.pl/~mkepski/ds/uf.html'>UR Fall Detection Dataset</a> -- It contains 70 videos illustrating `FALL` and `ADL` events. It also provides RGB and Depth data for each video.
We've utilized the RGB frames for this work and augmented the dataset by employing common augmentation techniques (e.g. rotation, flipping, etc.). <br>
<br/>
![sample_data](https://github.com/moshiurtonmoy/Fall-Detection-with-Federated-Transfer-Learning/blob/master/sample.png)

## Citation
```
@InProceedings{10.1007/978-981-99-8937-9_64,
author="Mistry, Durjoy
and Tonmoy, Moshiur Rahman
and Anower, Md. Shahib
and Hasan, A. S. M. Touhidul",
title="Federated Transfer Learning for Vision-Based Fall Detection",
booktitle="Proceedings of the 2nd International Conference on Big Data, IoT and Machine Learning",
year="2024",
publisher="Springer Nature Singapore",
address="Singapore",
pages="961--975"
}
```
