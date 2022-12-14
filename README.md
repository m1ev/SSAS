<p style="text-align:center"><h1>Программа для анализа звуковых сигналов</h2></p>
<p>Учебный проект для проведения анализа звуковых сигналов.</p>

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
 
 *<h4>Главное окно программы (2 режима отображения окон сигнала):</h4>*
 
 ![Главное окно программы 1](https://github.com/Turquoise69/SSAS/blob/main/readme_assets/1.jpg)
 <br><br>
 ![Главное окно программы 2](https://github.com/Turquoise69/SSAS/blob/main/readme_assets/3.jpg)
 <br>
 *<h4>Возможность масштабирования сигналов:</h4>*
 
 ![Возможность масштабирования сигналов](https://github.com/Turquoise69/SSAS/blob/main/readme_assets/1.png)
 <br>
 *<h4>Настройка масштаба шкалы:</h4>*
 
 ![Настройка масштаба шкалы](https://github.com/Turquoise69/SSAS/blob/main/readme_assets/2.png)
 <br>
 *<h4>Окно анализа спектрограммы участка сигнала:</h4>*
 
 ![Окно анализа спектрограммы участка сигнала](https://github.com/Turquoise69/SSAS/blob/main/readme_assets/1.gif)
  
 
 
 
