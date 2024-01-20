I wrote multiple blog posts in 2019-present which relied on older methods of NLP, older Solidity tools, etc.
My goal is to link the old blog posts to a header in this README and update one central repo as these
changes occur.

## Anti-Explanations

No new updates

## Arabic NLP

### Datasets (various uses)

https://twitter.com/zaidalyafeai/status/1448667731675398145

### Dialect + Generative Model

- My new model based on AraGPT2, with ArabertPreprocessor: https://huggingface.co/monsoon-nlp/dialect-ar-gpt-2021
- https://sites.google.com/view/nadi-shared-task
- https://twitter.com/CamelNlp/status/1328427861657722881
- https://aclanthology.org/2021.wanlp-1.1/

### Pre-trained Language Models

- generative model: AraGPT2, with ArabertPreprocessor on data https://huggingface.co/models?search=aragpt2
- masked language model: https://huggingface.co/models?filter=ar

### Sentiment Analysis

TBD

## Blockchain

- Islamic Finance eBook / GitHub: https://islamicfinance-book.github.io/ - new URL
- Flint language is rarely maintained / unmaintained: https://github.com/flintlang/flint

## Census API

I wrote an update about using the 2020 Census API and calculating 6+ race population by state and county https://blog.georeactor.com/census-1

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

Large-scale Facebook / Meta project: https://ai.facebook.com/blog/measure-fairness-and-mitigate-ai-bias/

## I18n

- Brave browser added many translations to MetaMask wallet, including RTL languages
- To find and share translations for cryptocurrency: https://github.com/nanexcool/defi18n

## JAX tutorials

A video tutorial: https://www.youtube.com/watch?v=SstuvS-tVc0

Notebook tutorials: https://github.com/AakashKumarNain/TF_JAX_tutorials

## Model Editing

- Deleting / forgetting information from models continues to be active research.
-- Counterfactuals in avoiding memorized sequences in models https://arxiv.org/abs/2112.12938

- Patching / updating models continues to be active research.

## Model Introspection

TBD

## Model training

For large transformer models, use Transformers / Trainer

## Negative results

No updates

## NLP + AAVE

- Annotator bias when labeling toxicity of AAE/AAVE language https://arxiv.org/abs/2111.07997

## Object recognition / YOLO

- OOD detection for object recognition https://arxiv.org/abs/2202.01197

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
- Google mSLAM multilingual model for text and speech https://arxiv.org/abs/2202.01374

## Thai NLP

Pretrained models: 

- WangchanBERTa https://huggingface.co/airesearch/wangchanberta-base-att-spm-uncased
- HoogBERTa https://github.com/lstnlp/HoogBERTa

Or largest pretrained ByT5 model you can use: https://huggingface.co/models?search=byt5

## Tokenization

- Measuring loss on specific tokens during GPT2 finetuning, and dearth of examples in GPT-NYC dataset https://mapmeld.medium.com/measuring-loss-on-new-gpt-tokens-7a4ab570a5df

## Toxicity / Hate Speech in NLP

Latest overview post: https://mapmeld.medium.com/its-not-easy-being-clean-ee217ed4825c

Perspective API is available for more languages: https://developers.perspectiveapi.com/s/about-the-api-attributes-and-languages

Video thesis defense around 'finding and fixing undesirable behaviors' of language models https://www.youtube.com/watch?v=BgcU_kytMf8

Annotator bias when labeling toxicity of AAE/AAVE language https://arxiv.org/abs/2111.07997

New effort to create a dataset: https://github.com/surge-ai/toxicity

A "Red Team" language model helping find problem responses in other language models https://deepmind.com/research/publications/2022/Red-Teaming-Language-Models-with-Language-Models

Request permission to access this dataset: https://huggingface.co/datasets/irlab-udc/metahate
