## Table of Contents
1. [Project title](#project-title)
2. [Project introduction](#project-introduction)
   - 2.1. [Objective](#objective)
   - 2.2. [Motivation](#motivation)
3. [Dataset description](#dataset-description)
   - 3.1. [Experiment Setup](#experiment-setup)
   - 3.2. [Data Aquisition](#data-aquisition)
   - 3.3. [Dataset Download](#dataset-download)
4. [Event Codes](#event-codes)
   - 4.1. [Each Class](#each-class)
   - 4.2. [Start and End of the Experiment](#start-and-end-of-the-experiment)
   - 4.3. [Channel Labels](#channel-labels)
5. [Reference](#Reference)

## 1. Project title: Imagined Speech Classification for Intuitive BCI Communication System

## 2. Project Introduction

### 2.1. Objective

The objective of our research in the field of Brain-Computer Interface (BCI) is to develop an intuitive communication system that benefits individuals with severe motor disabilities and lays the foundation for versatile technology applicable in everyday life. Specifically, we aim to classify and decode neural signals associated with the generation of words, enabling a direct and efficient means of communication for individuals with motor impairments. Simultaneously, we strive to create a platform that can be adapted for broader societal use.

### 2.2. Motivation
Our motivation is twofold. Firstly, we are committed to enhancing the quality of life for individuals with severe motor disabilities who often face challenges in expressing their thoughts and emotions. By developing a BCI system that deciphers imagined speech-related brainwave patterns, we aim to provide them with a lifeline to connect with the world. Secondly, we are inspired by the prospect of building a forward-looking system that can transcend medical applications. We envision a future where brain-computer communication becomes seamlessly integrated into everyday life, revolutionizing how we interact with technology and each other. This vision propels our research, as we believe that universal access to advanced communication tools can usher in a new era of inclusivity and convenience. By pushing the boundaries of BCI technology, we aim to shape a future where communication knows no bounds, benefiting individuals of all abilities and society as a whole.

## 3. Dataset Description

### 3.1. Experimental Setup
This experiment aimed to classify multi-class imagined speech with robust performance. Imagined speech of five words/phrases for basic communication ('hello,' 'help me,' 'stop,' 'thank you,' and 'yes') was recorded. During the experiment, subjects were seated in a comfortable chair in front of a 24-inch LCD monitor screen. Subjects were instructed to imagine the silent pronunciation of the given word as if they were performing real speech without moving any articulators or making sounds. They were strictly directed not to engage in any other brain activity but the given task. An auditory cue of the five words/phrases was randomly presented for 2 seconds, followed by 0.8-1.2 seconds of a cross mark. Subjects were instructed to perform imagined speech of the given cue as soon as the cross mark disappeared on the screen. After performing four times of imagined speech, 3 seconds of relaxation phase were given to clear up the mind for the next word/phrase.

### 3.2. Data Acquisition
The EEG data were recorded with an EEG signal amplifier (BrainAmp, BrainProduct GmbH, Germany). The raw data were recorded using BrainVision (BrainProduct GmbH, Germany) with MATLAB 2019a (The MathWorks Inc., USA). 64 EEG electrodes following a 10-20 international configuration were used for the recording. Ground and reference channels were placed on the Fpz and FCz. The impedance of all electrodes between the sensors and the skin of the scalp was maintained below 15kΩ.

### 3.3. Dataset Download
To obtain the Imagined Speech Dataset, [click here](https://drive.google.com/file/d/1Rrro7t1ZmWr8sHkluwf3vchTZzWYrcPG/view?usp=drive_link).


## 4. Event Codes

### 4.1. Each Class

| Class     | Event Code |
|-----------|------------|
| Hello     | 1          |
| Help me   | 2          |
| Stop      | 3          |
| Thank you | 4          |
| Yes       | 5          |

### 4.2. Start and End of the Experiment (a Whole Session)

| Class | Event Code |
|-------|------------|
| Start | 13         |
| End   | 14         |

## 4.3. Channel Labels

| Channel No. | Channel Label | Channel No. | Channel Label | Channel No. | Channel Label | Channel No. | Channel Label |
|-------------|---------------|-------------|---------------|-------------|---------------|-------------|---------------|
| 1           | Fp1           | 16          | T8            | 31          | O2            | 46          | FT10          |
| 2           | Fp2           | 17          | TP9           | 32          | PO10          | 47          | C5            |
| 3           | F7            | 18          | CP5           | 33          | AF7           | 48          | C1            |
| 4           | F3            | 19          | CP1           | 34          | AF3           | 49          | C2            |
| 5           | Fz            | 20          | CP2           | 35          | AF4           | 50          | C6            |
| 6           | F4            | 21          | CP6           | 36          | AF8           | 51          | TP7           |
| 7           | F8            | 22          | TP10          | 37          | F5            | 52          | CP3           |
| 8           | FC5           | 23          | P7            | 38          | F1            | 53          | CPz           |
| 9           | FC1           | 24          | P3            | 39          | F2            | 54          | CP4           |
| 10          | FC2           | 25          | Pz            | 40          | F6            | 55          | TP8           |
| 11          | FC6           | 26          | P4            | 41          | FT9           | 56          | P5            |
| 12          | T7            | 27          | P8            | 42          | FT7           | 57          | P1            |
| 13          | C3            | 28          | PO9           | 43          | FC3           | 58          | P2            |
| 14          | Cz            | 29          | O1            | 44          | FC4           | 59          | P6            |
| 15          | C4            | 30          | Oz            | 45          | FT8           | 60          | PO7           |

## 5. Reference
J. H. Jeong et al., "2020 International brain–computer interface competition: A review," *Frontiers in Human Neuroscience*, Vol. 16, 2022, p. 898300.
