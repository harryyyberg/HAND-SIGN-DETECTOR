Hand Sign Detector

This project is my attempt to build a simple sign language recognition system using computer vision.

The goal was to understand how gesture detection works without directly jumping into heavy deep-learning models. So instead of training a neural network, I worked on learning how images can be processed, how hand shapes can be analyzed, and how those patterns can be mapped to meaningful signs.

Right now, the system can recognize around 5–6 different hand gestures.

**What this project does
**
I collected sample images for each gesture and wrote logic to:

process the hand image

extract important visual information

compare it with known patterns

and finally display which sign it represents

It’s a small step toward sign language translation, but a big step in understanding the foundations of vision-based recognition.

**How it works (simple idea)
**
The program takes an image → studies the hand structure → checks which known gesture it is closest to → then prints the assigned label.

No big models, no huge datasets — just core concepts and implementation.

**Current abilities
**
Detects a limited set of predefined signs
Works on stored image inputs
Easy to modify and extend
Good for learning how real gesture systems begin

**Built With
**
Python

OpenCV & basic image processing

Custom comparison / decision logic

**What I want to improve next
**
In future versions, I’d like to:

support more gestures

improve detection accuracy

move to real-time webcam recognition

and eventually try ML/DL approaches

If you are a beginner trying to understand how sign recognition starts at the basic level, this project might help you.
