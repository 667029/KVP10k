# LayoutMv3 modell fintrent på KVP10K med relasjonslag
Dette repositoriet inneholder filer som viser prosessen og utviklingen av modellen vår.

## Endelig resultat
- Dataset_prosessor.ipnyb | Denne filen prosseserer KVP10K datasettet til et huggingface format som layoutmodellen kan bruke.
- LayoutMv3_KVP10k_ferdigstilt_V2.ipnyb | Denne filen er den finjusterte modellen vi trente på KVP10K datasettet.
- LayoutLMvl3_KVP10K_Relation_Model_Final.ipynb | Denne filer er den endelige layoutmodellen med et relasjonslag.

## Tidligere forsøk
- LayoutLMv3_kvp10k_Relation_layer.ipynb | Denne filen er et av forsøkene vi gjorde hvor vi brukte Pytouch
- Relation_model_final.ipnyb | Denne filen er det siste forsøket vi hadde før vi byttet løp til den endelige løsningen hvor bi brukte Tensorflow.

## Github repository for KVP10k-datasettet
- https://github.com/IBM/KVP10k



## Kjøring av prosjektet
Prosjektet kan kjøres på en enhet som støtter jupyter filer eller via colab

rekkefølge:
- Dataset_processor.ipnyb
- LayoytMvl3_KVP10k_ferdigstilt_V2.ipnyb
- LayoytMvl3_KVP10K_Relation_Model_Final.ipnyb
