# NgokoKrama
An Indonesian, Javanese Ngoko, Javanese Krama parallel corpus

## Summary
NgokoKrama is a parallel corpus consist of 1000 sentence pairs in Indonesian, Javanese Ngoko, and Javanese Krama (Alus). This dataset was built from UD-Javanese_CSUI dataset by **Alfina et al, 2024** (https://github.com/UniversalDependencies/UD_Javanese-CSUI) by evaluating the Indonesian-Javanese sentence pairs and translate them into Javanese Krama version with human validation.

## Research Paper
The research entitled **From Corpus to Benchmark: Evaluating Pretrained Language Models for Indonesian-Javanese Krama Translation** is published in IALP 2025. The article reported our preliminary experiment in using NgokoKrama to evaluate three pretrained language models (PLMs) for machine translation task between Indonesian and Javanese Krama. Those PLMs are IndoBART-v2, Indo-T5-v2-NusaX, and NLLB-200-600M-distilled. We conducted on-the-fly split with 80-10-10 setup by defining a random seed to make sure the split always produce the same result. However we also provide the split result in the dataset file as well. 

## Acknowledgment
This study was supported by the Faculty of Computer Science, Universitas Indonesia
