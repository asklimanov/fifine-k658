# Настройка микрофона Fifine K658

НАСТРОЙКА:

Для начала необходимо установить <a href="https://sourceforge.net/projects/equalizerapo/files/1.3/EqualizerAPO64-1.3.exe/download">Equalizer APO</a> и выбрать микрофон на вкладке Capture devices в Configurator. Компьютер перезагрузится.

* Уровень громкости микрофона в системе: 100<br>
* Ручка регулятора громкости на корпусе: 100% (максимум)<br>

Порядок настройки:

1. Разместить нужные 64-битные DLL плагины в папке "C:\Program Files\VSTPlugins\". Если папки нет, создать.<br>
2. Закинуть config.txt в папку "C:\Program Files\EqualizerAPO\config\"<br>
3. Выбрать микрофон в качестве устройства ввода в Configuration Editor (самый первый фильтр)<br>

Если пути горят красным (File not found), значит нужных плагинов нет по адресу "C:\Program Files\VSTPlugins\", выбирать плагины вручную в Equalizer APO не нужно, настройки собъются. Лучше положить нужные плагины в эту папку и перезапускать программу пока при запуске Equalizer APO не пропадёт красная надпись. Сравните имя файла в папке VSTPlugins и имя файла, которое написано в config.txt, они должны совпадать.<br>

ПЛАГИНЫ:

<b>config.txt</b> содержит настройки, которые исправляют очевидные проблемы АЧХ микрофона, добавляют де-эссер, компрессор и лимитер. Найти фаб плагины, которые используются в пресете можно ВКонтакте в файлах по запросу "FabFilter2", размер файла для сверки 4.8 МБ, расширение ".7z". Найти De-Esser, который используется в пресете можно ВКонтакте в файлах по запросу "accusonus4", размер файла для сверки 50.8 МБ, расширение ".7z". Если файлы не находятся, следует вбивать название в поиске по буквам, а не копировать из этого текста. Необходимо включить отображение расширений файлов в системе для установки VST плагинов. Для распаковки можно использовать архиватор 7-Zip.

Внимание! Для использования микрофона в режиме Proximity необходимо открутить ветрозащиту, приподнять ее приблизительно на половину и зафиксировать. В таком режиме можно говорить непосредственно в торец экрана, на расстоянии 3-5 см и получить плотный звук без поп-артефактов.
