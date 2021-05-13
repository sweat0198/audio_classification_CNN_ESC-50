# Audio Classification with CNN for ESC-50 dataset

Audio classification model which uses CNN to train ESC-50 dataset.  

## Getting Started

```
git clone https://github.com/sweat0198/audio_classication_CNN_ESC-50/tree/master
```

### Prerequisites

```
matplotlib>=2.0.0
pandas>=0.21.1
Keras>=2.1.3
tensorflow>=1.5.0
scipy>=1.0.0
librosa>=0.5.1
scikit_learn>=0.19.1
IPython>=7.8.0
tqdm>=4.48.0
jupyter
notebook

```

### Running

There are simply a jupyter notebook and codes are explained there.

## Built With

* [Kaggle-notebook](https://www.kaggle.com/docs/notebooks) - Kaggle notebook used run notebook
* [Pycharm](https://www.jetbrains.com/pycharm/) - Pycharm is used for working on local machine

## Achievements and Outcomes

* Data extended to 5 times with autmentation functions after splitting data as %70 training, %20 validating and %10 testing.
* Model reached to 0.850 accuracy with 0.640 loss in 46 epochs which has 32 batch size.
* Testing made with unseen data by the model, so 0.85 accuracy satisfies the expectations.

## Researches
			
| Git Repositories  | Comments |
| ------------- | ------------- |
|[karolpiczak/ESC-50](https://github.com/karolpiczak/ESC-50)  | Dataset of 50 classes which each has 40 audio file |
| [shibuiwilliam/audio_classification_keras](https://github.com/shibuiwilliam/audio_classification_keras)  | Well designed notebook, best accuracy with unseen test files. This is the choosen one.  |
| [micah5/pyAudioClassification](https://github.com/micah5/pyAudioClassification) | Dead Simple Usage, there exist svm, conv1d and conv2d algorithms. To who just want to classify some audio quickly.  |
| [seth814/Audio-Classification](https://github.com/seth814/Audio-Classification)  | With youtube tutorial, it uses Conv1d, Conv2D and LSTM. Could not tested since it cuts audio files.  |
| [drscotthawley/panotti](https://github.com/drscotthawley/panotti)  | Favorite repo because it has a lot useful tools, but accuracy up to 55 with ESC-50  |
| [bheemnitd/Environmental-Sound-Classification](https://github.com/bheemnitd/Environmental-Sound-Classification)  | Could not evaluate correctly since it has mixed augmented data in test and train  |
| [mtobeiyf/audio-classification](https://github.com/mtobeiyf/audio-classification)  | It has also svm, basic neural network and conv1d but accuracies of them are not high enough. Their max accuracy was 0.512  |
| [adanRivas/CNN-Audio-Classifier-with-Keras-Tensorflow](https://github.com/adanRivas/CNN-Audio-Classifier-with-Keras-Tensorflow)  | 65 accuracy with VGG16, pure data, may be it can be retrain with augmented data  |


## Acknowledgments

* https://github.com/shibuiwilliam/audio_classification_keras codes are taken from this repo and some modifications made on it.
### Inspirations: <br>
* https://github.com/adanRivas/CNN-Audio-Classifier-with-Keras-Tensorflow
* https://github.com/drscotthawley/panotti


## TODO

- [x] Make the prediction flexible in time.

