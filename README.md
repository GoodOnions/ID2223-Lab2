# Lab 2 for ID2223 Course @ KTH

**Keywords:** scalable machine learning, data engineering, classification, model ensemble
<p align="center">
    <img src="https://raw.githubusercontent.com/GoodOnions/ID2223-Lab1/main/imgs/goodonions_cover.png" alt="GoodOnions Official Repository"/>
</p>

## Team

**Name:** GoodOnions\
**Components:** [Daniele Cipollone](https://github.com/dancip00), [Federico Bono](https://github.com/FredBonux)

## Project description
The project is based on fine-tuning the [Wisper model](https://huggingface.co/openai/whisper-small), specializing it in one's native language. In our case, we used Italian.

To achieve this, we employed the reduced version of Wisper, namely Wisper-small, allowing reasonable fine-tuning times even on less powerful graphics cards, with this reduced model having 244 million parameters. For fine-tuning, we utilized a portion of the  [Common voice](https://huggingface.co/datasets/mozilla-foundation/common_voice_11_0/viewer/sv-SE/train) dataset.

Specifically, we used:
- 10,000 examples for training
- 2,500 examples for testing
The fine-tuning process was carried out using the Hugging Face library. In particular, we utilized the Trainer class, which allows for a simple and fast fine-tuning process.

Image of wisper model architecture:
<p align="center">
    <img src="https://cdn-images-1.medium.com/max/800/1*aSdK_bRq3bhrXpP_TdgIHg.png" alt="Wisper Architecture"/>

  



