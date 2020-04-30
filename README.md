# XCOPA: A Multilingual Dataset for Causal Commonsense Reasoning

The Cross-lingual Choice of Plausible Alternatives dataset is a benchmark to evaluate the ability of machine learning models to transfer commonsense reasoning across languages. The dataset is the translation and reannotation of the English [**COPA**](https://people.ict.usc.edu/~gordon/copa.html) ([**Roemmele et al. 2011**](#cite)) and covers 11 languages from 11 families and several areas around the globe. The dataset is challenging as it requires both the command of world knowledge and the ability to generalise to new languages. All the details about the creation of XCOPA and the implementation of the baselines are available in the [**paper**](#).

[**Languages**](#languages) | [**Baselines**](#baselines) | [**Cite**](#cite) | [**Paper**](#)

## Languages

| ISO 639-2 | Name | Family | Area* |
|---|---|---|---|
| et | Estonian | Uralic | Northern Europe |
| ht | Haitian Creole | French Creole | Carribean |
| id | Indonesian | Austronesian | Southeastern Asia |
| it | Italian | Indo-European | Southern Europe |
| qu | Quechua | Yuman–Cochimí | Southern America |
| sw | Swahili | Niger-Congo | Eastern Africa |
| ta | Tamil | Dravidian | Southern Asia |
| th | Thai | Kra-Dai | Southeastern Asia |
| tr | Turkish | Turkic | Western Asia |
| vi | Vietnamese | Austroasiatic | Southeastern Asia |
| zh | Mandarin Chinese | Sino-Tibetan | Eastern Asia |

\* According to the United Nations geoscheme.

## Baselines

![](baselines.pdf)

## Cite

If you use the data from this repository, please cite both XCOPA and the original COPA paper ```\cite{roemmele2011choice}```.

```
@inproceedings{roemmele2011choice,
  title={Choice of plausible alternatives: An evaluation of commonsense causal reasoning},
  author={Roemmele, Melissa and Bejan, Cosmin Adrian and Gordon, Andrew S},
  booktitle={2011 AAAI Spring Symposium Series},
  year={2011},
  url={https://people.ict.usc.edu/~gordon/publications/AAAI-SPRING11A.PDF},
}
```
