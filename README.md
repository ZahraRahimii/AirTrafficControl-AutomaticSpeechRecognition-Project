# Air-Traffic-Control-Automatic-Speech-Recognition-Project
Here are the steps of implementing an automatic speech recognition system for air traffic control communication dataset:

* first phase; searching for relevant articles and presenting them in PowerPoint format
* second phase: fine-tuning the [wav2vec2-large-xlsr-53](https://huggingface.co/facebook/wav2vec2-large-xlsr-53) model on the [ShEMO](https://www.kaggle.com/datasets/mansourehk/shemo-persian-speech-emotion-detection-database) (Persian Speech Emotion Detection) database
* third phase: fine-tuning the [wav2vec2-base](https://huggingface.co/facebook/wav2vec2-base) model on the English Timit dataset
* fourth phase: fine-tuning the [wav2vec2-large-robust](https://huggingface.co/facebook/wav2vec2-large-robust) model on air traffic dataset

## First phase; searching for relevant journals and presenting
After searching for various journals on this subject with the help of my group mate, I came to [this google sheet](https://docs.google.com/spreadsheets/d/1wMYELUeoU_0Zm-7DSxgvi75dt_lHJN4Pjh5Zmora5ZA/edit#gid=0) and then myself in [this google sheet](https://docs.google.com/spreadsheets/d/1qtfRcjFPwGst_EaaVl4-wRIdnllZLLy7rjCE4i-RkDU/edit#gid=0) lead to select the reference article titled [How Does Pre-trained Wav2Vec 2.0 Perform on Domain Shifted ASR? An Extensive Benchmark on Air Traffic Control Communications](https://arxiv.org/abs/2203.16822?context=cs.CL). Morever I presented a summary of what I received in [this PowerPoint](https://github.com/ZahraRahimii/Air-Traffic-Control-Automatic-Speech-Recognition-Project/blob/master/AsrGooyesh-Internship-FinalPresentation-ZahraRahimi.pptx).

## Second phase: Fine-tuning the wav2vec2-large-xlsr-53 model on the ShEMO (Persian Speech Emotion Detection) database
Running the code on availabe on [HuggingFace](https://huggingface.co/m3hrdadfi/wav2vec2-large-xlsr-persian-shemo), to understand what fine-tuning the model is and how it should be done on my mother tongue language to make the the preprocessing steps and results more comprehensible.
<!-- I came into this result:
![Capture](https://user-images.githubusercontent.com/93929227/203249576-b14533ae-dd91-4c56-b063-554c7859f6d5.PNG)  -->

## Third phase: Fine-tuning the wav2vec2-base model on the English Timit dataset
Running the code available on [HuggingFace](https://huggingface.co/blog/fine-tune-wav2vec2-english), to get closer to the main project which is in English.

## Fourth phase: Fine-tuning the wav2vec2-large-robust model on air traffic dataset
The dataset that was used was [ATCOSIM](https://www.spsc.tugraz.at/databases-and-tools/atcosim-air-traffic-control-simulation-speech-corpus.html). It consists of ten hours of speech data, which were recorded during ATC realtime simulations, automatically segmented, and orthographically transcribed. The utterances are in
English language and pronounced by ten non-native operational controllers. 
![ATCOSIM_Dataset_Corpus](https://user-images.githubusercontent.com/93929227/203252260-0e34fcc1-c6fc-4561-b9b0-134a3a3155dc.png)
