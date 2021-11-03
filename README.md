I wrote multiple blog posts in 2019-present which relied on older methods of NLP, older Solidity tools, etc.
My goal is to link the old blog posts to a header in this README and update one central repo as these
changes occur.

## Anti-Explanations

No new updates

## Arabic NLP

### Datasets (various uses)

https://twitter.com/zaidalyafeai/status/1448667731675398145

### Dialect + Generative Model

Based on AraGPT2, with ArabertPreprocessor: https://huggingface.co/monsoon-nlp/dialect-ar-gpt-2021

### Pre-trained Language Models

- generative model: AraGPT2, with ArabertPreprocessor on data https://huggingface.co/models?search=aragpt2
- masked language model: https://huggingface.co/models?filter=ar

### Sentiment Analysis

TBD

## Blockchain

- Islamic Finance eBook / GitHub: https://islamicfinance.github.io/
- Flint language is rarely maintained / unmaintained: https://github.com/flintlang/flint

## Census API

No new changes

## Crowdfunded AI 

No updates

## Facial recognition

- No updates on head coverings datasets

## Gender bias

Shown that embedding bias was not reflected in model output biases https://twitter.com/seraphinagt/status/1400769594005000192

## Gender re-inflection

My Arabic seq2seq model: https://huggingface.co/monsoon-nlp/ar-seq2seq-gender-decoder

My Spanish seq2seq model: https://huggingface.co/monsoon-nlp/es-seq2seq-gender-decoder

Updated and expanded Arabic dataset from NYU AD: https://camel.abudhabi.nyu.edu/arabic-parallel-gender-corpus/

## I18n

- Brave browser added many translations to MetaMask wallet, including RTL languages

## JAX tutorials

TBD

## Julia lang

TBD on classification

## Model Editing

- Deleting / forgetting information from models continues to be active research.
- Patching / updating models continues to be active research. The post-processing scores which I used here were completely off.

## Model Introspection

TBD

## Model training

For large transformer models, use Transformers / Trainer

## Negative results

No updates

## NLP + AAVE

No updates

## Object recognition / YOLO

TBD

## OpenStreetMap

- Keep using iD editor!
- Google Open Buildings Dataset is compliant with OSM (but download not available in regions and countries with conflicts serious enough for Google censorship)
- Detecting vandalism: Facebook released a small-ish dataset https://daylightmap.org/2021/05/24/name-vandalism-corpus-release.html
- OSM user embeddings: https://media.ccc.de/v/sotm2021-academic-10188-introducing-openstreetmap-user-embeddings-promising-steps-toward-automated-vandalism-and-community-detection

## Reddit datasets

- PushShift.io is the best place to download Reddit data
- Using Reddit as a source was highly criticized in Delphi moral AI project

## South Asian Language Model Projects

- Use Google's MuRIL model for Hindi, Tamil, Bangla, and other main languages of India (original and transliterated to Latin alphabet). [HuggingFace](https://huggingface.co/models?search=muril) and [TFHub](https://tfhub.dev/google/MuRIL/1) links.
- I have a few transfer learning experiments for Dhivehi , and local developers created TTS https://huggingface.co/models?filter=dv

## Text Augmentation and Attack Libraries

No new changes

## Text To Speech

- Kinyarwanda and Luganda are success stories on Mozilla CommonVoice
- TTS library continues to be developed by Coqui

## Thai NLP

Pretrained models: WangchanBERTa https://huggingface.co/airesearch/wangchanberta-base-att-spm-uncased

Or largest pretrained ByT5 model you can use: https://huggingface.co/models?search=byt5

## Tokenization

No new changes

## Toxicity / Hate Speech in NLP

Latest overview post: https://mapmeld.medium.com/its-not-easy-being-clean-ee217ed4825c

Perspective API is available for more languages: https://developers.perspectiveapi.com/s/about-the-api-attributes-and-languages
