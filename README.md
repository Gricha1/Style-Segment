Горбов Г.В. Статья оформленная для Липановских чтений(краткое введение).

ВКР_Горбов_Конец Полный текст дипломной работы
# Style-Segment
Алгоритма для переноса стиля на фон изображения.
Реализуется первичная сегментация обьета(предполагается, что обьект один), а затем накладывается стиль.
# Модели
Для сегментации изображения были использованы модели - ResNet101, ResNet50 (попиксильное обьединение результатов этих двух моделей дало наилучишй результат)
Для переноса стиля был использован и немного изменен алгоритм NST. 

# Результаты
![Marina](https://user-images.githubusercontent.com/64344132/123556051-3770b200-d79a-11eb-9a7e-e093b934d4f9.jpg)
![VanDark](https://user-images.githubusercontent.com/64344132/123556054-3ccdfc80-d79a-11eb-8351-bc7308175da1.jpg)
![MarinaStyled](https://user-images.githubusercontent.com/64344132/123556024-22941e80-d79a-11eb-94b0-36eb8b865554.jpg)


![bear](https://user-images.githubusercontent.com/64344132/123556069-4e170900-d79a-11eb-8189-66886da2f563.jpg)
![Fire](https://user-images.githubusercontent.com/64344132/123556065-49525500-d79a-11eb-8372-19ee67edbd8b.jpg)
![FireBear](https://user-images.githubusercontent.com/64344132/123556062-45263780-d79a-11eb-9d46-3e4731e18491.png)
