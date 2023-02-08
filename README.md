# MUCA Gesture Recognition

## overview

in this repo you can find various gesture recognition models for the MUCA dataset.

## gestures

| Gesture | gif |
| --- | --- |
| slidedown| ![slidedown](/GIFS/slidedown.gif) |
| slideup| ![slideup](/GIFS/slideup.gif) |
| slideleft| ![slideleft](/GIFS/slideleft.gif) |
| slideright| ![slideright](/GIFS/slideright.gif) |
| longtouch| ![longtouch](/GIFS/longtouch.gif) |

## current model

we compare the derivative of the x,y coordinates of chosen points of interest. the points of interest are chosen by performing floodflilling on the image and then choosing the points with the highest value.

The result is the following mean derivative per class:

![pictures of mean derivatives](/GIFS/mean_derivatives.png)

## current accuracy:


| label | accuracy |
| --- | --- |
| slidedown | 0.878261 |
| slideright | 0.835821 |
| longtouch | 0.966292 |
| slideup | 0.753012 |
| slideleft | 0.708661 |


## TODO

- [ ] add more models
- [ ] change how the model is tested to use more frames# MUCAGesture
