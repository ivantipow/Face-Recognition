# Face Recognition

![low](https://github.com/ivantipow/Face-Recognition/blob/main/faces.png)

В этом репозитории мы создадим и обучим небольшую систему распознавания лиц, обучим её с различными функциями потерь, имплементируем различные метрики для оценки качества работы модели.

---------

## Содержание
- [`1. NN for Faces Classification.ipynb`](https://github.com/ivantipow/Face-Recognition/blob/main/1.%20NN%20for%20Faces%20Classification.ipynb) - блокнот, в котором мы дообучим Inception Resnet V1 классифицировать лица из CelebA dataset, имплементируем TPR@FPR метрику, оценим качество работы получившейся модели.

- [`2. Loss functions for Faces Classification.ipynb`](https://github.com/ivantipow/Face-Recognition/blob/main/2.%20Loss%20functions%20for%20Faces%20Classification.ipynb) - блокнот, в котором мы имплементируем два популярных лосс в задаче распознавания лиц: Triplet Loss и ArcFace Loss, а также обучим нашу сеть с ними.



## Дополнительные ссылки
- Данный репозиторий выполнен в рамках обучения в [Deep Learning School](https://www.dlschool.org/).
- Srivastava Y., Murali V., Dubey S. R. [A performance evaluation of loss functions for deep face recognition](https://arxiv.org/pdf/1901.05903.pdf).
- Deng J. et al. [Arcface: Additive angular margin loss for deep face recognition](https://arxiv.org/pdf/1801.07698.pdf).
