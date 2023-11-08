# Neutral TTS Female Voice Corpus in Brazilian Portuguese

This is the landing page for extra content regarding the work &quot;Neutral TTS Female Voice Corpus in Brazilian Portuguese&quot;.


In the next section, you can find sintetized examples and details about the experiments conducted in the paper. 

## Access
The dataset is fully available at [kaggle](https://www.kaggle.com/mediatechlab/gneutralspeech), under [this license](https://www.smt.ufrj.br/~gpa/terms_of_use.pdf). The full paper can be found at the [SBRT's library](https://biblioteca.sbrt.org.br/articles/4464).

### **Note on phoneme distribution**
We would like to show that the phoneme distribution of the data presented in our work is in fact in tone with the Brazilian Portuguese language and compatible with other datasets in Brazilian Portuguese. For that, we compare the phoneme distribution with the [WikiText PT-BR text corpus](https://igormq.github.io/datasets/), which contains more than 8 million utterances in Brazilian Portuguese, and also with another important [dataset](https://github.com/Edresson/TTS-Portuguese-Corpus) of Brazilian portuguese speech. The phoneme representations were obtained using the [phonemizer github library](https://github.com/bootphon/phonemizer).

![images/histogram_PT_BR_Wiki_Ours.png](images/histogram_PT_BR_Wiki_Ours.png)

![images/histogram_TTS_PT_Ours.png](images/histogram_TTS_PT_Ours.png)

As we can perceive, the phoneme distribution in this dataset is compatible with the portuguese language and thus should be able to reproduce all phonemes needed to train Brazilian Portuguese voice synthesis modules.
