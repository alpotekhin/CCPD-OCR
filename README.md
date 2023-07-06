# Chinese City Parking OCR


**Input sample:** 
![Автомобильный номер](https://algocode.ru/files/course_dlfall22/number.png)

**Output sample:** 皖AD16688

## Model architecture
CRNN model with CTC-loss is implemented

![Архитектура](https://algocode.ru/files/course_dlfall22/architecture.png)

## Corpus
[CCPD2019](https://github.com/detectRecog/CCPD) is used for train and CCPD-weather for test.

## Results
0.95 accuracy and 0.009 CER score
