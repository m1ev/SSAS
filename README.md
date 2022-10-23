<p style="text-align:center"><h1>Speech Signal Analysis Software</h2></p>
<p>Один из ранних вариантов моего первого учебного проекта, предназначенного для проведения анализа звуковых сигналов.</p>

<h2>Описание</h3>

 #### Настоящая программа позволяет открывать несжатые звуковые данные в импульсно-кодовой модуляции в формате WAVE и производить следующие операции:
 
 - Прочитывать заголовок файла-контейнера WAVE и выводить информацию на экран
 - Отображать сигналограмму открытого WAVE файла с возможностью масштабирования изображения с использованием библиотеки _OpenGL_
 - Проводить операцию математической свертки открытого звукового сигнала с одним из трех сгенерированных сигналов (ядром свертки) и выводить их сигналограммы на экран
 - Воспроизводить открытые звуковые сигналы с помощью компонента _DirectSound_ библиотеки _DirectX_
 - Производить анализ спектра выбранного участка открытого звукового сигнала с возможностью применения окон сглаживания
<br>
 <h2>Основные программные модули</h2>
 
 * Unit1.pas - основной программный модуль
 * window1.pas, window2.pas, window3.pas - модули окон анализа сигналов
 * Ogl.pas - модуль отрисовки изображений проекта
 * Spectrum.pas - модуль проведения математических операций над сигналами (вычисление спектра, свертки и т.д.)
 <br>
 <h2>Изображения</h2>
 
 <p><h4>Главное окно программы:</h4></p>
 ![Главное окно программы](https://github.com/Turquoise69/SSAS/blob/main/readme_assets/1.jpg)
 
 
