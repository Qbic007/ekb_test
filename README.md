<h1>Тестовое задание для ЭКБ</h1>

Для запуска приложения необходимо:
- создать БД, соответствующие настройки отразить в ekb_test/config/db.php
- рименить миграции (yii migrate).

Алгоритм приложения следующий:
1. принимает от пользователя целое число и массив целых чисел
2. делит массив по ПРАВИЛУ (описано ниже)
3. возращает результат, в случае успеха, либо -1 в остальных случаях

ПРАВИЛО: Необходимо разделить входной массив таким образом, чтобы количество чисел N в первой части оказалось равно
количеству чисел не равных N во второй и это количество должно быть больше 0.

Приложение реализовано двумя методами:

1. в виде консольной команды array N ARRAY, где N - входное целое число, ARRAY - входной массив целых чисел (для передачи массива необходимо записать целые числа через запятую без пробелов)
2. в виде web-интерфейса с формой ввода входных параметров. При этом форма ввода параметров доступна только для авторизованных пользователей.
Тестовые данные для авторизации:
admin/admin
demo/demo

