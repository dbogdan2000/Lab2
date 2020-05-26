# Lab2
В задаче используется сёрточная сеть. В процессе выполнения изменялось количество слоёв Conv2D и параметр filters.

1.Свёрточная нейронная сеть с двумя слоями Conv2D(filters=32, kernel_size=3), lr = 1*10^(-9), epoch=100, BATCH_SIZE = 2;
 Графики метрики точности:

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Acc:%20Batch%20%3D%202%3B%202%20Conv2D32:32%2C3:3%3B%20epoch%20%3D%20100%20.png)

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Val_acc:%20Batch%20%3D%202%2C%202%20Conv2D32:32%2C3:3%3B%20epoch%20%3D%20100%20.png)

 Графики функции потерь:
  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Loss:%20Batch%20%3D%202%2C%202%20Conv2D32:32%2C3:3%3B%20epoch%20%3D%20100%20.png)

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Val_loss:%20Batch%20%3D%202%2C%202%20Conv2D32:32%2C3:3%3B%20epoch%20%3D%20100%20.png)

2.Свёрточная нейронная сеть с двумя слоями Conv2D(filters=64, kernel_size=3), lr = 1*10^(-9), epoch=120, BATCH_SIZE = 2;
 Графики метрики точности:
  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Acc:%20Batch%20%3D%202%2C%202%20Conv2D64:64%2C3:3%3B%20epoch%20%3D%20120%20.png)

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Val_acc:%20Batch%20%3D%202%2C%202%20Conv2D64:64%2C3:3%20epoch%20%3D%20120%20.png)

 Графики функции потерь:
  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Loss:%20Batch%20%3D%202%2C%202%20Conv2D64:64%2C3:3%20epoch%20%3D%20120%20.png)

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Val_loss:%20Batch%20%3D%202%2C%202%20Conv2D64:64%2C3:3%3B%20epoch%20%3D%20120%20.png)

3.Свёрточная нейронная сеть с тремя слоями Conv2D(filters=32, kernel_size=3), lr = 1*10^(-9), epoch=100, BATCH_SIZE = 2;
 Графики метрики точности:
  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Acc:%20Batch%20%3D%202%2C%203%20Conv2D(32:32:32%2C3:3:3)%2Clr%20%3D%200%2C000000001%2C%20epoch%20%3D%20100%20.png)

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Val_acc:%20Batch%20%3D%202%2C%203%20Conv2D32:32:32%2C3:3:3%20epoch%20%3D%20100%20.png)

 Графики функции потерь:
  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Loss:%20Batch%20%3D%202%2C%203%20Conv2D32:32:32%2C3:3:3%3B%20epoch%20%3D%20100%20.png)

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Val_loss:%20Batch%20%3D%202%2C%203%20Conv2D32:32:32%2C3:3:3%3B%20epoch%20%3D%20100%20.png)

4.Свёрточная нейронная сеть с двумя слоями Conv2D(filters=64, kernel_size=3) и одним слоем Сonv2D(filters = 128, kernel_size=3), lr = 1*10^(-9), epoch=100, BATCH_SIZE = 2;
 Графики метрики точности:
  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Acc:%20Batch%20%3D%202%2C%203%20Conv2D128:64:64%2C3:3:3%3B%20epoch%20%3D%20100%20.png)

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Val_acc:%20Batch%20%3D%202%2C%203%20Conv2D128:64:64%2C3:3:3%3B%20epoch%20%3D%20100%20.png)

 Графики функции потерь:
  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Loss:%20Batch%20%3D%202%2C%203%20Conv2D128:64:64%2C3:3:3%20epoch%20%3D%20100%20.png)

  ![Image alt](https://github.com/dbogdan2000/Lab2/blob/master/Val_loss:%20Batch%20%3D%202%2C%203%20Conv2D128:64:64%2C3:3:3%20epoch%20%3D%20100%20.png)

