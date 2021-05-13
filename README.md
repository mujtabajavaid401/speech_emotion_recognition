#  Speech Emotion Recognition

# Overview

In this project I am trying to develop a system that is able to detect human emotion based on a persons voice.

I am using a dataset that contains voices of a number people which are labelled by a number of annotators in-terms of the emotions the tone and pitch of these voices indicate i.e anger or happy etc 

Just like from images these voices are are processed to extract features which a model can understand and use to it for classifications purposes.

These features that are extracted include mfcc or Mel Frequency Cepstral Coefficient that indicates the short-term power spectrum of a sound, chroma and mel or Mel Spectrogram Frequency.

The zero crossing rate is the rate of sign-changes along a signal, i.e., the rate at which the signal changes from positive to negative or back. This feature has been used heavily in both speech recognition and music information retrieval. It usually has higher values for highly percussive sounds like those in metal and rock.

Spectral Centroid, indicates where the ”centre of mass” for a sound is located and is calculated as the weighted mean of the frequencies present in the sound. If the frequencies in music are same throughout then spectral centroid would be around a centre and if there are high frequencies at the end of sound then the centroid would be towards its end.

Spectral rolloff is the frequency below which a specified percentage of the total spectral energy, e.g. 85%, lies.

# Dataset

Link : https://drive.google.com/file/d/1wWsrN2Ep7x6lWqOXfr4rpKGYrJhWc8z7/view