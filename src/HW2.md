<font size = 5><b>Задание: Запустить контейнер с ubuntu, используя механизм LXC. 
Ограничить контейнер 256 Мб ОЗУ и проверить, что ограничение работает. </b></font>
<font size = 4>
1. Переходим в режим sudo:
![](Containerization_HW2_1.png)
2. Проверяем обновления: 
![](Containerization_HW2_2.png)
3. Установливаем пакет lxc-templates, содержащий шаблоны для создания контейнеров:
![](Containerization_HW2_3.png)
4. Устанавливаем значения по умолчанию: 
![](Containerization_HW2_4.png)
5. Проверяем: 
![](Containerization_HW2_5.png)
6. Создаем контейнер: 
![](Containerization_HW2_6.png)
7. Запускаем контейнер, входим в него и проверяем память: 
![](Containerization_HW2_7.png)
8. Выходим из контейнера, закрываем его и открываем конфигурацию: 
![](Containerization_HW2_8.png)
9. Ограничиваем память до 256М: 
![](Containerization_HW2_9.png)
10. Выходим и проверяем: 
![](Containerization_HW2_10.png)
</font>