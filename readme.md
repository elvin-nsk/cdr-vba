# Каталог макросов

В этот каталог входит или постепенно войдёт вспомогательный софт для CorelDraw, соответствующий критериям: 
- VBA-макросы (то есть распространяемые в формате `gms`), аддоны в формате `dll` или `cpg`, а так же докеры. Либо всё сразу в одном.
- Наличие русского или хотя бы английского интерфейса (если таковой вообще нужен).

Изначально в каталог планировалось добавлять только свободно распространяемые макросы, но временно в этот каталог добавлены и платные.

**Значок у ссылки:**

- без значка - страничка и/или папка с файлами находится в каталоге
- :octocat: - ссылка на ресурс на github'е
- :earth_africa: &#47; :earth_americas: - внешняя ссылка на русскоязычный / англоязычный ресурс
- :moneybag: - платный макрос, всегда по внешней ссылке

## Документ, страницы
- [BitExAll](https://forum.rudtp.ru/resources/x8-iz-korelovskogo-fajla-vytaschit-rastrovye-kartinki.1955/) :earth_africa: - Экспортирует растровые картинки из документа.
- [ExPDF](https://forum.rudtp.ru/threads/publish-to-pdf.78812/) :earth_africa: - Экспорт в ПДФ текущей или всех страниц документа
с заданными параметрами по цвету, разрешению растра, местоположению и наличию вылетов.
- [ExportJPG](catalog/ExportJPG) - Экспорт документа постранично в растровые или векторные файлы.
- [File Name Inserter (PathLabel)](catalog/PathLabel) - Вставляет имя файла документа на страницу(ы).

## Допечатная подготовка
- [Выравнивание объектов (Alignemento)](https://github.com/elvin-nsk/promacro01_Alignemento_RU) :octocat: - Укладчик на лист.
- [Convert to Curves (CtC)](catalog/CtC) - Допечатная проверка (префлайт), автоматический фикс цветности, чёрного, эффектов, растра, прозрачности, обводок. Must have.
- [Tiler](catalog/Tiler) - Укладчик на лист. Настройка припусков, расстояний, установка меток.

## Метки, направляющие, шаблоны
- [EyeletMarking](http://www.corelvba.com/index.php?pages=eyelet_1) :earth_americas: - Расстановка меток для установки люверсов. Возможность задать диаметр люверса, расстояние между люверсами, формирование поля под загиб. Проверен в работе на версиях 15 и 17.
- [Quick Margins](catalog/QuickMargins) - Для работы с направляющими. Создает сразу четыре направляющие относительно границ листа. Можно задать отступ для каждой или для всех четырех сразу. Проверен в работе на версиях 15 и 17.
- [SetGuidelines](http://corelvba.com/index.php?pages=setguide_1) :earth_americas: - Установка направляющих. Проверен в работе на версиях 15 и 17.
- [Templater](catalog/Templater) - Шаблоны направляющих для визитки, дисконтной карты, карманного календаря, календаря "домика", буклета и брошюры.

## Переменные данные
- [BestGenerator](https://bestgenerator.smartprepress.ru) :moneybag: - Макрос для пакетного размещения в макете любых переменных (серийных номеров, штрих-кодов и QR-кодов, текстов, изображений). Для версий 17 и выше.

## Плоттерная резка
- [DevelopmentSign](http://corelvba.com/index.php?pages=develop_1) :earth_americas: - Макрос для построения развёртки боковой поверхности объемной буквы с линиями сгиба.
- [DirectEnpack](https://github.com/fersatgit/DirectEnpack#readme) :octocat: - cpg-аддон для компоновки прямоугольных объектов на лист. Не для резки гильотиной. Nesting-укладчик, написанный на ассемблере. 
- [eCut](http://www.plotcalc.com) :moneybag: - Софт, работающий через корел. Подготовка файлов для плоттерной/фрезерной резки, расчет стоимости выполнения работ, а так же непосредственно вывод на плоттер. Так же программа имеет в своем арсенале функции для расчета световых вывесок, построения кассет из композитных материалов и многое другое.
- [PlotCalc](http://www.plotcalc.com) :moneybag: - Предназначен для дизайнеров, занимающихся порезкой на плоттере. Вывод на порезку, сортировка, измерение длины кривых, измерение площади фигур, схема в масштабе, поиск точек пересечения.

## Поиск, получение информации
- [Geometric Information](https://smartprepress.ru/GeometricExt.gms) :earth_asia: - Расчёт площади, периметра, объёма сложных фигур.
- [ObjectFinder](https://github.com/elvin-nsk/ObjectFinder) :octocat: - Поиск объектов по размеру.
- [Select Same](catalog/SelectSame) - Позволяет находить объекты, похожие на выделенный, по разным признакам.
- [Takoi ili Ne Takoi](https://github.com/elvin-nsk/TakoiNeTakoi) :octocat: - Тоже позволяет находить объекты, похожие на выделенный, по разным признакам.

## Текст
- [Corrector](catalog/Corrector) - Сброс параметров текста, замена символов, удаление лишних символов.

## Цвет, заливка
- [Color Replacer](catalog/ColorReplacer) - Замена цвета в объектах/заливках в нужном диапазоне.
- [Mirror Fountain Fill](catalog/MirrorFF) - Позволяет в один клик отзеркалить сложные градиентные заливки, что невозможно сделать стандартными возможностями CorelDRAW. Проверен в работе на версиях 15, 16.

## Эффекты
- [HighLights](http://www.corelvba.com/index.php?pages=high_1) :earth_americas: - Делает эффект типа emboss (впукливание/выпукливание). Заявлена совместимость с версиями 13–17.

## Прочее
- [Adjust Objects; Retain Positions (AORP)](https://community.coreldraw.com/share/b/eskimo/posts/21-macro---aorp-adjust-objects-retain-positions) :earth_americas: - Макрос для массовой трансформации объектов, аналог макроса `Transform Each`. Завявлена совместимость с версиями 17–21.
- [Bitmap Tools](https://github.com/elvin-nsk/BitmapTools) :octocat: - Редактирование растровых картинок из корела в фотошопе.
- [RemoveUnderlyingDups](catalog/RemoveUnderlyingDups) - Макрос находит и удаляет дубликаты объектов, лежащих друг на друге.
- [SmartDepart](https://github.com/fersatgit/SmartDepart#readme) :octocat: - cpg-аддон для разбиения или объединения кривых с учётом их вложенности
- [SyncWindowsToggle](catalog/SyncWindowsToggle) - Макрос создает второе окно для документа, в котором синхронно отображает в режиме wireframe (каркас).
- [TablePresetDocker](catalog/TablePresetDocker) - Докер. Графические пресеты для таблиц.
- [Thumbnailer](https://www.oberonplace.com/vba/drawmacros/thumbnailer/index.htm) :earth_africa: - Импортирует файлы из указанной папки и создаёт для них превьюшки на листе.
- [Transform Each](https://forum.rudtp.ru/threads/macros-transform-each-v-2.70491/) :earth_asia: - Макрос для массовой трансформации объектов. Изменение масштаба, поворот и прочее применяются к каждому из выделенных объектов.

## Сборники
- [Grafisin Macro Collections](http://www.grafisin.com/2018/04/free-macro-collections-2018-for.html) :earth_americas: - Сборник разных небольших макросов от индонезийских товарищей, на английском языке: дупликация, замена текста, замена цвета, нумерация, создание превьюшек, фрактальные эффекты, метки реза и прочее.
- [RionFreeScripts](http://www.rion.ru/information/scripts/) :earth_africa: - Макросы от типографии "Рион": перевод текста в кривые, замена цвета, замена параметров обводки, экспорт в jpeg, допечатная проверка (префлайт), создание векторного штрих-кода.
- [wOxxOm Tools](https://github.com/elvin-nsk/wx_Tools) :octocat: - Известный сборник макросов от wOxxOm.




## Полезные статьи

- [Установка макросов](articles/installation.md)
- [Если макрос не работает](articles/vba-repair.md)

## Интересные ресурсы
- [Awesome VBA](https://github.com/sancarn/awesome-vba#readme) :octocat: - Awesome-лист полезных ресурсов для программирования на VBA.