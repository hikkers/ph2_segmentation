# Image segmenation

<p align="middle">
	<img src="/assets/example.png">
</p>

В данном ноутбуке содержится имплементация разных архитектур сверточных нейронных сетей для решения задачи сегментации изображений.
Имплементированы следующие модели:
<br>
**[Segnet](https://arxiv.org/pdf/1511.00561.pdf)**
<br>
**[Unet](https://arxiv.org/pdf/1505.04597.pdf)**
<br>

Для обучения сверточных нейронных сетей был использован датасет PH2. Датасет состоит из 200 снимков поражений кожи и их сегментированных изображений.

<img src="/assets/dataset_sample.png">

## Segnet
<p align="middle">
	<img src="/images/segnet.png">
</p>

###Segnet результаты

<p align="middle">
	<img src="/images/segnet_res.png">
</p>

##Unet

<p align="middle">
	<img src="/images/unet.png">
</p>

###Unet результаты
<p align="middle">
	<img src="/images/unet_res.png">
</p>

###Unet-2
В данной имплементации **Unet** операции **Maxpooling** и **Upsample** заменены на сверточные слои **Convolutions** и **Transpose-convolutions**.


###Unet-2 результаты
<p align="middle">
	<img src="/images/unet2_res.png">
</p>

##Заключение
