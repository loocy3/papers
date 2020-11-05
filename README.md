# papers
These two papers are the assignments of my university course. Both are classify tasks by using deep networks.

Abstract of Landmark Recognition Report:
When we browse the Internet, we are often attracted by
some charming views. Sometimes people can recognize
them quickly, but most of the time, people can not. Our
challenge is to create a novel image recognition network
that can help people recognize the landmark efficiently and
correctly. In contrast to normal image recognition problem
with limited class, the Google Landmarks Datasetv2
(GLDv2) [9] is a benchmark for large scale, fine-grained
instance recognition in the domain of human made and natural
landmarks. The GLDv2 contains more than 5 million
images and over 200k different classes. Additionally, the
datasets are extremely long-tailed class distribution, a large
fraction of non-landmark test photos and large intra-class
variability. We introduced our model with the combination
of non-landmark classifier module and multiple landmark
classifiers module to solve this problem under limited
classes and images due to the limited computational resources.
In the non-landmark classifier, we use the ResNet
[4] as backbone and deep neural network (DNN) to reduce
feature dimension to speed up process time. In the multilandmark
classifier stage, we combine the efficientNet [8]
and the Arcface loss [2] to solve large intra-class variability.
The performance of our method can achieve 0:25 global
average precision (GAP) within only 10 epochs.

Abstract of MultiEmotiCon_report:
Emotion plays an important role in humans’ daily life. Throughout different emotions,
humans build different relationships with others and take various actions to
respond to their emotions. Currently, scientists propose accurate facial expressions
models to predict emotions. However, we can also refer to surroundings to improve
the accuracy of emotion recognition. In this paper, we propose an end to end
network to extract the features of face, body, background, depth and semantic
segmentation, and use these features to predict emotions. Finally, we test our
method on EMOTIC and the result has 1% improvement when compared with the
Kosti’s result.
