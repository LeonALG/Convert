# Convert
Программма преобразует данные, которые были записаны на предприятии, в ходе механических ударных испытаний, анализирует их и накапливает характеристики испытания:
1. Выделение момента очередного удара установки по изделию;
2. Подсчет количества ударов;
3. Определение его параметров: момент срыва платформы ударной установки, сила удара, окончание колебаний после удара.
В файле «Result.txt» содержится информация о результатах тестирования, а именно: количество ударов, моменты очередного удара установки по изделию, параметры удара.
В файле «test.txt» содержатся преобразованные данные с АЦП Е14-440.
В файле «data.dat» содержатся значения ускорений, полученных с АЦП Е14-440 на протяжении всего испытания.
Для работы программы необходимо запустить Convert.exe и выбрать частоту. Результат анализа будет показан на экране, а также сохранен в файл "Result.exe".
Для графического просмотра данных, полученных с АЦП Е14-440, необходимо воспользоваться программой: https://github.com/LeonALG/VKR_Graph
Полная информация о разработанной подсистеме находится здесь: https://github.com/LeonALG/Convert