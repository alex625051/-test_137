# -test_137
Тестовое задание Python
# quick Start

1) Указать значения переменных для подключения к БД:
  - POSTGRESuser
  - POSTGRESpassword
  - POSTGREShost
  - POSTGRESport
  - POSTGRESdatabase
  - POSTGREStable
  
2) Создать таблицу test в базе данных:
  CREATE TABLE test
  >(
  >    № INTEGER,
  >    "заказ №" INTEGER PRIMARY KEY,
  >    стоимость DECIMAL,
  >    "срок поставки" DATE,
  >    "стоимость в руб." DECIMAL
  >);
  
3) Установить библиотеки:
  > pip install -r requirements.txt

4) запустить скрипт:
  > python test_137.py
  
5) Для отсановки выполнения скрипта:
  > Нажать клавиши [ctrl]+C
