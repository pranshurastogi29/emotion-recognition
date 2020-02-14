# emotion-recognition

# The project

The scope of this project is to create a classifier to predict the emotions of the speaker starting from an audio file.

**Dataset**

For this task, I have used 4948 samples from the RAVDESS dataset (see below to know more about the data).

The samples comes from:

- Audio-only files;

- Video + audio files: I have extracted the audio from each file using the script **videotoaudio.py** that you can find in the main directory of the project.

The classes we are trying to predict are the following: (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised)

# Result of the application of a Neural Network to this dataset

**93.9%** accuracy on the training set and **90.1%** on the test set.

# Loss and accuracy plots

![Link to loss](https://github.com/pranshurastogi29/emotion-recognition-ravdess/blob/master/media/loss.png) 

![Link to accuracy](https://github.com/pranshurastogi29/emotion-recognition-ravdess/blob/master/media/accuracy.png)


**Download**

The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) can be downloaded free of charge at https://zenodo.org/record/1188976. 


**Description**

The dataset contains the complete set of 7356 RAVDESS files (total size: 24.8 GB). Each of the 24 actors consists of three modality formats: Audio-only (16bit, 48kHz .wav), Audio-Video (720p H.264, AAC 48kHz, .mp4), and Video-only (no sound).  Note, there are no song files for Actor_18.

