# awesome-turkish-vlm
A curated list of models, datasets and other useful resources for Turkish Vision-Language Models (VLM).

## Content
- [awesome-turkish-vlm](#awesome-turkish-vlm)
  - [Content](#content)
  - [🚀 Introduction](#-introduction)
  - [🤖 Models](#-models)
  - [📚 Datasets](#-datasets)
  - [🧑‍💻 Code](#-code)
    - [📓 Notebooks](#-notebooks)
    - [🔗 Repositories](#-repositories)

## 🚀 Introduction

This repository is an awesome list of curated resources dedicated to Turkish Vision-Language Models (VLM). It includes pretrained/fine-tuned models, datasets, and related works you need to get started or deepen your research in Turkish multimodal AI.

Contributions and suggestions are warmly welcomed! 🌟

## 🤖 Models

> [!NOTE]  
> We prioritize adding models that explicitly state in their documentation or model card that they have been trained for Turkish. However, other models that are observed to perform well with Turkish in practice may also be included.

|Name|Size|License|
|:---|:---|:------|
|[ytu-ce-cosmos/Turkish-LLaVA-v0.1](https://huggingface.co/ytu-ce-cosmos/Turkish-LLaVA-v0.1)|8B|MIT|
|[TraVisionLM-base](https://huggingface.co/ucsahin/TraVisionLM-base)|875M|Apache 2.0|
|[TraVisionLM-DPO](https://huggingface.co/ucsahin/TraVisionLM-DPO)|875M|Apache 2.0|
|[TraVisionLM-Object-Detection-ft](https://huggingface.co/ucsahin/TraVisionLM-Object-Detection-ft)|875M|Apache 2.0|
|[mistralai/Mistral-Small-3.2-24B-Instruct-2506](https://huggingface.co/mistralai/Mistral-Small-3.2-24B-Instruct-2506)|24B|Apache-2.0|
|[mistralai/Mistral-Small-3.1-24B-Instruct-2503](https://huggingface.co/mistralai/Mistral-Small-3.1-24B-Instruct-2503)|24B|Apache-2.0|
|[CohereLabs/aya-vision-8b](https://huggingface.co/CohereLabs/aya-vision-8b)|8B|CC-BY-NC-4.0|
|[CohereLabs/aya-vision-32b](https://huggingface.co/CohereLabs/aya-vision-32b)|32B|CC-BY-NC-4.0|
|[utter-project/EuroVLM-1.7B-Preview](https://huggingface.co/utter-project/EuroVLM-1.7B-Preview)|1.7B|Apache-2.0|
|[utter-project/EuroVLM-9B-Preview](https://huggingface.co/utter-project/EuroVLM-9B-Preview)|9B|Apache-2.0|
|[Gemma 3](https://huggingface.co/collections/google/gemma-3-release-67c6c6f89c4f76621268bb6d)|4B-12B-27B|Gemma|
|[Qwen2-VL](https://huggingface.co/collections/Qwen/qwen2-vl-66cee7455501d7126940800d)|2B-7B-72B|Apache-2.0|
|[Qwen2.5-VL](https://huggingface.co/collections/Qwen/qwen25-vl-6795ffac22b334a837c0f9a5)|3B-7B-32B-72B|Apache-2.0|

## 📚 Datasets 

|Name|Description|Size|License|
|:---|:----------|:---|:------|
|[ytu-ce-cosmos/turkce-kitap](https://huggingface.co/datasets/ytu-ce-cosmos/turkce-kitap)|Book cover collection designed to improve the Turkish OCR ability.|108k||
|[ytu-ce-cosmos/Turkish-LLaVA-Pretrain](https://huggingface.co/datasets/ytu-ce-cosmos/Turkish-LLaVA-Pretrain)|Pretraining dataset for Turkish base VLM.|595k||MIT|
|[ytu-ce-cosmos/Turkish-LLaVA-Finetune](https://huggingface.co/datasets/ytu-ce-cosmos/Turkish-LLaVA-Finetune)|Fine-tuning dataset for Turkish VLM.|522k||
|[ucsahin/COCO-OD-TR-Single-Objects-v2](https://huggingface.co/datasets/ucsahin/COCO-OD-TR-Single-Objects-v2)|Combined dataset for object detection task.|153k||
|[ucsahin/Turkish-VLM-Mix-Benchmark](https://huggingface.co/datasets/ucsahin/Turkish-VLM-Mix-Benchmark)|Combined dataset for benchmark.|35k||
|[ucsahin/TR-VLM-DPO-Dataset](https://huggingface.co/datasets/ucsahin/TR-VLM-DPO-Dataset)|DPO formatted instruction-following dataset.|10k||
|[atasoglu/flickr30k-turkish](https://huggingface.co/datasets/atasoglu/flickr30k-turkish)|Turkish translation of the Flickr30k dataset.|30k||
|[atasoglu/flickr8k-turkish-mt](https://huggingface.co/datasets/atasoglu/flickr8k-turkish-mt)|Turkish translation of the Flickr8k dataset.|8k||
|[atasoglu/flickr8k-turkish](https://huggingface.co/datasets/atasoglu/flickr8k-turkish)|Native Turkish version of the Flickr8k dataset.|8k|CC0 1.0|
|[atasoglu/flickr8k-turkish-detailed-captions](https://huggingface.co/datasets/atasoglu/flickr8k-turkish-detailed-captions)|Flickr8k dataset with long captions.|8k|CC0 1.0|
|[99eren99/LLaVA1.5-Data-Turkish](https://huggingface.co/datasets/99eren99/LLaVA1.5-Data-Turkish)|Combined dataset for instruction-following.||CC BY 4.0|
|[mcemilg/laion2B-multi-turkish-subset](https://huggingface.co/datasets/mcemilg/laion2B-multi-turkish-subset)|Turkish subset of the Laion2b-multi.|34M|CC BY 4.0|
|[NexusAI-tddi/VisIT-Bench-tr](https://huggingface.co/datasets/NexusAI-tddi/VisIT-Bench-tr)|Bench dataset for instruction-following.|574||
|[umarigan/turkish_clip_dataset_with_text_embeddings](https://huggingface.co/datasets/umarigan/turkish_clip_dataset_with_text_embeddings)|Turkish-English caption pairs with embeddings.|410k|CreativeML Open RAIL-M|
|[YxBxRyXJx/cut_TRV_ver2_1019](https://huggingface.co/datasets/YxBxRyXJx/cut_TRV_ver2_1019)|Turkish object detection dataset.|2k||
|[selimc/tr-textbook-ColPali](https://huggingface.co/datasets/selimc/tr-textbook-ColPali)|Dataset for document retrieving from Turkish textbook.|3k||
|[muhammetfatihaktug/bilim_teknik_mini_colpali](https://huggingface.co/datasets/muhammetfatihaktug/bilim_teknik_mini_colpali)|Dataset for document retrieving from Turkish science magazine.|4k|MIT|
|[umarigan/PD12M-Turkish](https://huggingface.co/datasets/umarigan/PD12M-Turkish)|A large Turkish captioning dataset.|12M|CDLA-Permissive-2.0|

## 🧑‍💻 Code

### 📓 Notebooks

- [Finetuning TraVisionLM On Object Detection](https://colab.research.google.com/drive/1XXnG9QXOvuNtWkr9OPkx0GbnPLYGF-rV?usp=sharing)
- [Direct Preference Optimization (DPO) for Your Visual Language Model (VLM)](https://colab.research.google.com/drive/1ypEPQ3RBX3_X7m9qfmU-Op-vGgOjab_z?usp=sharing)
- [How to Finetune Florence-2 Model for Object Detection](https://colab.research.google.com/drive/1Y8GVjwzBIgfmfD3ZypDX5H1JA_VG0YDL?usp=sharing)
- [Turkish-LLaVA fine-tuning using 4bit QLoRA](https://colab.research.google.com/drive/1rgdK6-HVHYapmlBw04Lf66kgwhl7VSb1?usp=sharing)

### 🔗 Repositories

- [smol-vision](https://github.com/merveenoyan/smol-vision): Recipes for shrinking, optimizing, customizing cutting edge vision models.
- [turkish-llava-notebooks](https://github.com/atasoglu/turkish-llava-notebooks): Collection of notebooks for Turkish LLaVA model on various on various use-cases.
  
