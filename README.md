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

we compare the derivative of the x,y coordinates of the greatest value of each frame. the result is the following mean derivative per class:

![pictures of mean derivatives](/GIFS/mean_derivatives.png)

## current accuracy:


| label | accuracy |
| --- | --- |
| slidedown | 0.921739 |
| slideright | 0.711443 |
| longtouch | 0.674157 |
| slideup | 0.819277 |
| slideleft | 0.724409 |


## TODO

- [ ] add more models
- [ ] change how the model is tested to use more frames# MUCAGesture
