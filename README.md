# Speech-Translation

# Multilingual Speech Translator for Tamil and Telugu
# ABSTRACT
This project presents a comprehensive framework for direct speech-to-speech translation, employing a sophisticated pipeline integrating various modules to ensure accurate and fluent translation. At its core, the system utilizes a S2UT model, leveraging self-supervised learning techniques and k-means clustering to transform speech
signals into discrete units. Multitask learning enhances the model’s robustness by incorporating auxiliary tasks during training. Additionally, a unit-based vocoder, incorporating duration prediction, generates high-quality speech waveforms from the discrete units. Furthermore, a cascaded system approach integrates Automatic Speech
Recognition (ASR), Machine Translation (MT), and Text-to-Speech (TTS) modules,
each contributing to the seamless translation process. The system design emphasizes
high-performance computing resources and large-scale datasets for training, with attention to network connectivity and memory capacity. Implementation and testing reveal
promising results, with evaluations based on BLEU and PESQ scores. Overall, this research advances the field of speech translation, offering a sophisticated framework for
real-world applications in multilingual communication.


### Project Overview
This project aims to break down language barriers in a multilingual environment, particularly within higher education institutions, by creating a speech-to-speech translator for Tamil and Telugu. It eliminates the need for an intermediate language like English, ensuring more accurate translations. The system uses both direct speech-to-speech translation and a cascaded approach to provide seamless communication.

### Motivation
The diverse nature of university campuses, where several regional languages are spoken, often leads to communication challenges. By developing a multilingual translator, this project promotes inclusivity and enhances intercultural communication. The ultimate goal is to create a more vibrant and collaborative community where language is no longer a barrier but a bridge.

### Features
- **Direct Speech-to-Speech Translation**: Provides real-time translation between Tamil and Telugu without relying on an intermediate language.
- **Cascaded System**: Uses a combination of Automatic Speech Recognition (ASR), Machine Translation (MT), and Text-to-Speech (TTS) for highly accurate and natural translations.
- **Improved Accuracy**: Avoids information loss by removing intermediate languages, ensuring translations are contextually correct and culturally sensitive.

### System Architecture
1. **Speech-to-Unit Translation (S2UT)**: Converts speech into discrete units using self-supervised learning techniques.
2. **Multitask Learning**: Incorporates auxiliary tasks for better linguistic feature extraction.
3. **Unit-Based Vocoder**: Converts discrete units back into speech for natural-sounding output.
4. **Cascaded Systems**: 
   - ASR: Transcribes speech into text.
   - MT: Translates text into the target language.
   - TTS: Converts translated text back into speech.

### Tools and Technologies
- **FAIRSEQ S2ST**: For building and training the sequence-to-sequence translation model.
- **PyTorch**: Deep learning framework for implementing various modules.
- **Hugging Face Transformers**: Utilizes pre-trained models like HuBERT for faster integration and efficient translation.
- **HiFi-GAN & Fastspeech2**: For generating high-quality speech output.
- **Wav2Vec and Whisper**: Used for transcribing Tamil audio to text.
- **Google Colab**: For GPU-based model training.
- **NumPy & Pandas**: For data preprocessing and manipulation.

### System Requirements
- **Hardware**: 
  - Minimum 64 GB RAM.
  - CUDA-enabled GPU for accelerated processing.
  - Ample disk space for datasets and model checkpoints.
- **Software**: 
  - Python 3.8+
  - FAIRSEQ, PyTorch 2.3, Hugging Face Transformers, HiFi-GAN, Fastspeech2
  - NumPy 1.26.4, Pandas 2.2.2
  - Google Colab for training and deployment.



### Future Work
- Implementing deep learning models like **LSTM** and **CNN**.
- Exploring **BERT embeddings** for better text representation.
- Expanding the system to cover more Indian languages.

### Contributing
Feel free to contribute to this project by submitting issues or pull requests. Let's make this multilingual translator even better together!

Thank you for checking out this project! Let's work together to build a more inclusive, multilingual world.




