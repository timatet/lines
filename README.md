## Вычисление длин извилистых линий

### Возможности
Вычисление длин рек, представленных набором геодезических координат.

### Входные данные
Цельный объект, представленный geojson или shp файлом, содержащий координаты широты и долготы, характеризующие его. 

### Выходные данные
Результаты вычисления:
  * Вычисление суммы расстояний в метрах между последующими парами координат набора на сфероиде
  * Вычисление расстояния при использовании формулы гаверсинуса и значения радиуса Земли на сфероиде
  * Вычисление суммы расстояний в метрах между последующими парами координат набора на эллипсоиде WGS-84 

### Тестирование
  * fast_test
  * first_test
  * latest_test
