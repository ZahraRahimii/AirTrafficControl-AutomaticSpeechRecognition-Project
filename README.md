# Air-Traffic-Control-Automatic-Speech-Recognition-Project
Here are the steps of implementing an automatic speech recognition system for air traffic control communication dataset:

* first phase; searching for relevant articles and presenting them in PowerPoint format
* second phase: fine-tuning the [wav2vec2-large-xlsr-53](https://huggingface.co/facebook/wav2vec2-large-xlsr-53) model on the [ShEMO](https://www.kaggle.com/datasets/mansourehk/shemo-persian-speech-emotion-detection-database) (Persian Speech Emotion Detection) database
* third phase: fine-tuning the [wav2vec2-base](https://huggingface.co/facebook/wav2vec2-base) model on the English Timit dataset
* fourth phase: fine-tuning the [wav2vec2-large-robust](https://huggingface.co/facebook/wav2vec2-large-robust) model on air traffic dataset

## First phase; searching for relevant journals and presenting
After searching for various journals on this subject with the help of my group mate, I came to [this google sheet](https://docs.google.com/spreadsheets/d/1wMYELUeoU_0Zm-7DSxgvi75dt_lHJN4Pjh5Zmora5ZA/edit#gid=0) and then myself in [this google sheet](https://docs.google.com/spreadsheets/d/1qtfRcjFPwGst_EaaVl4-wRIdnllZLLy7rjCE4i-RkDU/edit#gid=0) lead to select the reference article titled [How Does Pre-trained Wav2Vec 2.0 Perform on Domain Shifted ASR? An Extensive Benchmark on Air Traffic Control Communications](https://arxiv.org/abs/2203.16822?context=cs.CL). Morever I presented a summary of what I received in [this PowerPoint](#AsrGooyesh-Internship-FinalPresentation-ZahraRahimi.pptx).

## Second phase: fine-tuning the wav2vec2-large-xlsr-53 model on the ShEMO (Persian Speech Emotion Detection) database
