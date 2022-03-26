# hse_hw3_chromhmm

### Клеточная линия - Osteobl
Ссылка на Colab: https://colab.research.google.com/drive/1f1TB2o4cEESY40_c_kqo7qKw6PUv5ely#scrollTo=HkNwxZvT05mT

Размер файлов в папке с выдачей ChromHMM не позволяет загрузить все файлы в репозиторий ==> ссылка на гугл диск с файлами: https://drive.google.com/drive/folders/1IF3de847IJ2EgPuIVl-FPyloG5xCngM2


## Гистоновые метки
**Метка** | **Файл** | 
------------ | ------------- | 
H2az | wgEncodeBroadHistoneOsteoblH2azStdAlnRep1.bam
H3k27ac| wgEncodeBroadHistoneOsteoblH3k27acStdAlnRep1.bam
H3k27me3| wgEncodeBroadHistoneOsteoH3k27me3AlnRep1.bam
H3k36me3| wgEncodeBroadHistoneOsteoblH3k36me3StdAlnRep1.bam
H3k4me1| wgEncodeBroadHistoneOsteoblH3k4me1StdAlnRep1.bam
H3k4me2| wgEncodeBroadHistoneOsteoblH3k4me2StdAlnRep1.bam
H3k4me3| wgEncodeBroadHistoneOsteoH3k04me3AlnRep1.bam
H3k79me2| wgEncodeBroadHistoneOsteoH3k79me2AlnRep1.bam
H3k9me3| wgEncodeBroadHistoneOsteoblH3k9me3StdAlnRep1.bam
H4k20me1| wgEncodeBroadHistoneOsteoH4k20me1AlnRep1.bam
CTCF | wgEncodeBroadHistoneOsteoblCtcfStdAlnRep1.bam
EP300 | wgEncodeBroadHistoneOsteoP300kat3bAlnRep1.bam

## Картинки ChromHMM

![emissions_10](https://user-images.githubusercontent.com/93256219/160252469-3cf1224b-2bda-490c-bb03-7d509fb84e52.png)

![Osteobl_10_overlap](https://user-images.githubusercontent.com/93256219/160252477-4ba9c3f3-77cf-4d5e-b908-d72fe120b0ae.png)

![Osteobl_10_RefSeqTES_neighborhood](https://user-images.githubusercontent.com/93256219/160252480-d1bdead3-a37d-4305-bf32-db05b81fa98b.png)

![Osteobl_10_RefSeqTSS_neighborhood](https://user-images.githubusercontent.com/93256219/160252482-7dbaacb9-d069-4299-b94c-27bce3c36e7c.png)

![transitions_10](https://user-images.githubusercontent.com/93256219/160252488-4b07a1af-6c48-4ce0-9cc3-354f8912530e.png)

##  USCS Genome Browser
### Chr1
1
![1](https://user-images.githubusercontent.com/93256219/160253272-b205b6ce-e32b-47a4-9bce-7ec0cfd07e6b.png)
![3](https://user-images.githubusercontent.com/93256219/160253323-48fd001c-d466-44a0-a393-04354dccd37b.png)


2
![11](https://user-images.githubusercontent.com/93256219/160253437-16ae4e00-49d7-45ac-a087-ca42a2b68c26.png)
![22](https://user-images.githubusercontent.com/93256219/160253439-2c0422ec-259d-40b0-bad2-63b0c65c9fd3.png)

## Таблица
**Эпигенетический тип** | **Описание** | **Метки** | **Состояние**
------------ | ------------- | ------------- | ------------- 
1 | наиболее часто встречается в TES и RefSeqGene, экзонах | H3k36me3 | Transcribed region
2 | наиболее часто встречается в  RefSeqGene| H4k20me1, H3k79me2, H3k36me3 | Transcribed region
3 | наиболее часто встречается в  RefSeqGene и TES | H3k4me3, H3k4me2, H3k27ac, H3k4me1, H3k79me2, H4k20me1 | Weak promoter
4 | гены, конец транскрипции| H2az, H3k4me2, H3k27ac, H3k4me1| Enhancer/Transcribed region	
5 | присутствует в lamina | H2az, H3k4me1 | Repressed heterochromatin
6 | встречается в TES и lamina, попадает на участки промотора| H2az, H3k4me3, H3k4me2, H3k27ac, H3k79me2 | Activate promoter 
7 | конец транскрипции, lamina, экзоны | CTCF | Heterochromatin
8 | большой процент во всем геноме, покрывает большие участки гена и попадает как в область энхансеров, так и промоторов, присутствует в lamina | - | Heterochromatin
9 | Конец транскрипции, экзоны,  CpG islands | EP300, H3k27me3 | Transcribed region  
10 | большой процент во всем геноме и lamina, не попадает на участки промоторов и энхансеров | - | Heterochromatin




