# Imagined Speech Classification for Intuitive BCI Communication System

## Project Introduction

### Objective
The objective of our research in the field of Brain-Computer Interface (BCI) is to develop an intuitive communication system that benefits individuals with severe motor disabilities and lays the foundation for versatile technology applicable in everyday life. Specifically, we aim to classify and decode neural signals associated with the generation of words, enabling a direct and efficient means of communication for individuals with motor impairments. Simultaneously, we strive to create a platform that can be adapted for broader societal use.

### Motivation
Our motivation is twofold. Firstly, we are committed to enhancing the quality of life for individuals with severe motor disabilities who often face challenges in expressing their thoughts and emotions. By developing a BCI system that deciphers imagined speech-related brainwave patterns, we aim to provide them with a lifeline to connect with the world. Secondly, we are inspired by the prospect of building a forward-looking system that can transcend medical applications. We envision a future where brain-computer communication becomes seamlessly integrated into everyday life, revolutionizing how we interact with technology and each other. This vision propels our research, as we believe that universal access to advanced communication tools can usher in a new era of inclusivity and convenience. By pushing the boundaries of BCI technology, we aim to shape a future where communication knows no bounds, benefiting individuals of all abilities and society as a whole.

## Dataset Description

### Experimental Setup
This experiment aimed to classify multi-class imagined speech with robust performance. Imagined speech of five words/phrases for basic communication ('hello,' 'help me,' 'stop,' 'thank you,' and 'yes') was recorded. During the experiment, subjects were seated in a comfortable chair in front of a 24-inch LCD monitor screen. Subjects were instructed to imagine the silent pronunciation of the given word as if they were performing real speech without moving any articulators or making sounds. They were strictly directed not to engage in any other brain activity but the given task. An auditory cue of the five words/phrases was randomly presented for 2 seconds, followed by 0.8-1.2 seconds of a cross mark. Subjects were instructed to perform imagined speech of the given cue as soon as the cross mark disappeared on the screen. After performing four times of imagined speech, 3 seconds of relaxation phase were given to clear up the mind for the next word/phrase.

### Data Acquisition
The EEG data were recorded with an EEG signal amplifier (BrainAmp, BrainProduct GmbH, Germany). The raw data were recorded using BrainVision (BrainProduct GmbH, Germany) with MATLAB 2019a (The MathWorks Inc., USA). 64 EEG electrodes following a 10-20 international configuration were used for the recording. Ground and reference channels were placed on the Fpz and FCz. The impedance of all electrodes between the sensors and the skin of the scalp was maintained below 15kΩ.
