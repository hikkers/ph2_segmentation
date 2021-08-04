# Image segmenation
![Image segmentation](/assets/example.png)

В данном ноутбуке содержится имплементация разных архитектур сверточных нейронных сетей для решения задачи сегментации изображений.
Имплементированы следующие модели:
**[Segnet](https://arxiv.org/pdf/1511.00561.pdf)**
**[Unet](https://arxiv.org/pdf/1505.04597.pdf)**

Для обучения сверточных нейронных сетей был использован датасет PH2. Датасет состоит из 200 снимков поражений кожи и их сегментированных изображений.

![Dataset example](/assets/dataset_sample.png)

## Segnet
<p align="middle">
	![Segnet](/images/segnet.png)
</p>

###Segnet результаты

<p align="middle">
	![Segnet res](/images/segnet_res.png)
</p>

##Unet

<p align="middle">
	![Unet](/images/unet.png)
</p>

###Unet результаты
<p align="middle">
	![Unet res](/images/unet_res.png)
</p>

###Unet-2
В данной имплементации **Unet** операции **Maxpooling** и **Upsample** заменены на сверточные слои **Convolutions** и **Transpose-convolutions**.


###Unet-2 результаты
<p align="middle">
	![Unet2 res](/images/unet2_res.png)
</p>

##Заключение
