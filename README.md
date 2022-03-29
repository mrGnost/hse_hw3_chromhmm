# Домашняя работа №3 по биоинформатике

> [код в гугл колабе с бонусным заданием в том числе](https://colab.research.google.com/drive/1drCBzQXp7zBS121PlmcA5H3Fng8c3bFT?usp=sharing)

# Таблица с гистоновыми метками
| Клеточная линия       | Гистоновая метка | Файл | Контрольный файл |
| ------------- |:---------------:| :---------------:| :------------------:|
| HepG2   |H2AFZ|H2azStdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K27ac|H3k27acStdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K27me3|H3k27me3StdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K36me3|H3k36me3StdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K4me1|H3k04me1StdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K4me2|H3k4me2StdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K4me3|H3k4me3StdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K79me2|H3k79me2StdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K9ac|H3k9acStdAlnRep1.bam|ControlStdAlnRep1.bam|
| HepG2   |H3K9me3|H3k09me3AlnRep1.bam|ControlStdAlnRep1.bam|

# Картинки из выдачи ChromHMM
![image](https://user-images.githubusercontent.com/61655850/160595084-d49eb685-90a9-44c5-94d2-60217638e4bb.png)
![image](https://user-images.githubusercontent.com/61655850/160595126-9b52bdeb-522b-459a-9e3c-8c53caeefbef.png)
![image](https://user-images.githubusercontent.com/61655850/160595197-91f9496f-c2d9-48c1-82b5-09d3c973b83a.png)
![image](https://user-images.githubusercontent.com/61655850/160595224-f97090b3-1b75-4d2b-8a4d-2d8eacec9f97.png)
![image](https://user-images.githubusercontent.com/61655850/160595263-5f917a41-d31b-4485-89c9-bf79263bc354.png)

# Эпигенетические типы
| Состояние       | Модификации гистонов | Эпигенетический тип |
| ------------- |:---------------:| :---------------:|
|1|-|Transcriptional elongation|
|2|H3K79me2|Weak transcribed|
|3|H3K79me2, H3K4me1|Transcriptional transition|
|4|H3K4me1|Weak enhancer|
|5|H3K4me2, H3K4me1, H3K9ac, H3K27ac|Strong enhancer|
|6|H3K4me3, H3K4me2, H3K9ac, H3K27ac|Active Promoter|
|7|H3K4me2, H3K4me1, H3K4me3|Weak Promoter|
|8|H3K27me3|Heterochromatin; low signal|
|9|-|Weak transcribed|
|10|H3K9me3|Weak transcribed|

![image](https://user-images.githubusercontent.com/61655850/160649576-f1f7dfd8-3ccd-447c-bbe5-5dc16c0c7851.png)
![image](https://user-images.githubusercontent.com/61655850/160649913-39a46d4a-5fc9-427f-8868-de7935240468.png)

# Доп. задание
>Файл находится в папке Доп_задание
![image](https://user-images.githubusercontent.com/61655850/160664169-fe74bfd6-ca5e-47d8-8b85-0a3f4d59d1b7.png)
