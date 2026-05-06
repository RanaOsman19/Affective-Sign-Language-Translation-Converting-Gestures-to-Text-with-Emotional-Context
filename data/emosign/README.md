---
license: cc-by-sa-4.0
---

# Dataset Card for EmoSign

The EmoSign dataset contains emotion labels of videos of individuals signing in American Sign Language.

## Dataset Details

### Dataset Description

Unlike spoken languages where the use of prosodic features to convey emotion is well studied, indicators of emotion in sign language remain poorly understood, creating communication barriers in critical settings. Sign languages present unique challenges as facial expressions and hand movements simultaneously serve both grammatical and emotional functions. To address this gap, we introduce EmoSign, the first sign video dataset containing sentiment and emotion labels for 200 American Sign Language (ASL) videos. We also collect open-ended descriptions of emotion cues. Annotations were done by 3 Deaf ASL signers with professional interpretation experience. This dataset not only addresses a critical gap in existing sign language research but also establishes a new benchmark for understanding model capabilities in multimodal emotion recognition for sign languages. 


- **Language(s) (NLP):** English
- **License:** CC-BY-SA


## Dataset Structure

Each row contains annotations for one video clip. 

The video name is the original video name + utterance.

The original sign videos and English captions can be obtained from [Boston University's ASLLRP Dataset](https://www.bu.edu/asllrp)


The labels are:
- Sentiment (-3: extremely negative to 3: extremely positive)
- Emotion, each labeled with the degree of presence (0: not present to 3: extremely present)
  - Joy
  - Excited
  - Surprise (Positive)
  - Surprise (Negative)
  - Worry
  - Sadness
  - Fear
  - Disgust
  - Frustration
  - Anger
- Attributions of emotional cues by each annotator (Reasoning_1, Reasoning_2, Reasoning_3)


## Dataset Card Contact

Cathy Fang: catfang[at]media[dot]mit[dot]edu