# Prodigy Infotech Task 4

## Task Description

Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

## Dataset

The dataset contains 20,000 images of hand guestures. The images are taken in infrared and have a size of 150x150 pixels. The dataset is divided into a training set and a test set with a split of 80/20.

## Deliverables

- A jupyter notebook containing the code for the hand gesture recognition model.
- Repository containing the dataset where the pictures are stored in the following
- A csv file containing the labels for the images in the dataset.

## Results and Discussion

VGG16 model was used to classify the images of hand gestures. The model was trained on the training set and evaluated on the test set. The model achieved an accuracy of 0.999 on the test set.

```
Test Accuracy: 0.9992499947547913
Precision for Each Class:
Precision for _c: 1.0000
Precision for _down: 1.0000
Precision for _fist: 0.9946
Precision for _fist_moved: 0.9975
Precision for _index: 1.0000
Precision for _l: 1.0000
Precision for _ok: 1.0000
Precision for _palm: 1.0000
Precision for _palm_moved: 1.0000
Precision for _thumb: 1.0000
```

## Conclusion

The SVM model was able to classify images of cats and dogs with high accuracy. The model can be used to classify images of cats and dogs in real-world applications.
