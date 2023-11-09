# Neutral TTS Female Voice Corpus in Brazilian Portuguese

This is the landing page for extra content regarding the work &quot;Neutral TTS Female Voice Corpus in Brazilian Portuguese&quot;.

## Abstract
This paper introduces a new dataset designed to address the limitations in high-quality, diverse and representative datasets for training text-to-speech (TTS) models, specifically for female voices in Brazilian Portuguese. The dataset features a female voice recorded in a professional and controlled environment with neutral emotion and comprises more than 20 hours of recordings. The goal is to facilitate transfer learning and enable the development of more natural-sounding, high-quality, and gender-balanced TTS systems. Alongside the dataset, gender-aware voice transfer experiments are performed to understand the impact of utilizing gender-specific pretrained models for speech synthesis. The results obtained show that same-gender voice transfer yields better speech similarity and intelligibility when compared to cross-gender transfer, emphasizing the importance of gender-aware training procedures and highlighting the need for balanced gender data.

## Access
The dataset is fully available at [kaggle](https://www.kaggle.com/datasets/mediatechlab/g-neutral-speech-female), under [this license](https://gpa-smt-ufrj.github.io/sbrt2023/terms_of_use.txt). The full paper can be found at the [SBRT's library](https://biblioteca.sbrt.org.br/articles/4464).

### **Note on phoneme distribution**
We would like to show that the phoneme distribution of the data presented in our work is in fact in tone with the Brazilian Portuguese language and compatible with other datasets in Brazilian Portuguese. For that, we compare the phoneme distribution with the [WikiText PT-BR text corpus](https://igormq.github.io/datasets/), which contains more than 8 million utterances in Brazilian Portuguese, and also with another important [dataset](https://github.com/Edresson/TTS-Portuguese-Corpus) of Brazilian portuguese speech. The phoneme representations were obtained using the [phonemizer github library](https://github.com/bootphon/phonemizer).

![images/histogram_PT_BR_Wiki_Ours.png](images/histogram_PT_BR_Wiki_Ours.png)

![images/histogram_TTS_PT_Ours.png](images/histogram_TTS_PT_Ours.png)

As we can perceive, the phoneme distribution in this dataset is compatible with the portuguese language and thus should be able to reproduce all phonemes needed to train Brazilian Portuguese voice synthesis modules.

