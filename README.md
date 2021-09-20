Human action detection in videos (i.e., series of images) plays an important role in various real-life applications (e.g., visual surveillance and automated driver assistance, surveillance to image and video understanding). Aerial human action detection has several other applications like surveillance using Unmanned Aerial Vehicle (UAV), which provides a wider range of view, higher performance, search and rescue tasks, and human interaction understanding.

The objective of this project is to analyse and provide a novel approach for human action detection using deep learning. I try to establish a specific pattern in my proposed approach.

With rigorous literature survey and reviews of current approches towards the task of human action detection, I have selected Okutama dataset for human action detection.

Challenges of HAR in aerial videos:

1) Variation of human sizes in videos.
2) Changing of altitude of the platform that camera is attached to.
3) Apperance of actor fades as resolution decreases.

### Output classes to learn how to classify
LABELS = [
'Carrying',
'Drinking',
'Hand Shaking',
'Lying',
'Reading',
'Running',
'Sitting',
'Standing',
'Walking'
]

## Input Data


## Training network
![alt text](https://github.com/AnshDesai/HAR-on-Okutama-Dataset/blob/master/network.png)


CONCLUSION:

Through this three approaches , I establish a pattern which is:

Accuracy is higher for model with LSTM + attention than LSTM and BI-LSTM models.

Focusing on specific regions and sequential(time) models prove to be better for classification for sequential data.

## References and citations:

https://www.mdpi.com/507920

Liu, Y.; Xu, K.; Xu, J. Periodic Surface Defect Detection in Steel Plates Based on Deep Learning.

Human Action Recognition using CNN and LSTM-RNN with Attention Model Pothanaicker, Kuppusamy. (2019). Human Action Recognition using CNN and LSTM-RNN with Attention Model. 8. 1639-1643.

Recurrently exploring class-wise attention in a hybrid convolutional and bidirectional LSTM network for multi-label aerial image classification https://doi.org/10.1016/j.isprsjprs.2019.01.015

## Future Enhancement:

1) Different models such as self attention, transformer network and graph attention mechanisms.
2) Compare the results with these approaches on more recent state-of-art datasets.

