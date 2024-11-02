# Лабораторная работа № 7
Создадим программу на языке Python, которая использует паттерн проектирования "Наблюдатель" для отслеживания изменений курсов валют через API Центробанка РФ. 
Программа запрашивает курсы валют и уведомляет зарегистрированных наблюдателей о изменении курсов через заданные интервалы времени (1 мин).

Наблюдатели-клиенты реализованы через html файл
[image1](https://github.com/vasiliza2/prog5_lr7/blob/b676d20c45a043e827089a71436d5bb1237364d3/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-11-02%20141100.png)

flask используется для создания веб-сервера - файл app.py

[image2](https://github.com/vasiliza2/prog5_lr7/blob/b676d20c45a043e827089a71436d5bb1237364d3/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-11-02%20140924.png)
[image3](https://github.com/vasiliza2/prog5_lr7/blob/b676d20c45a043e827089a71436d5bb1237364d3/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-11-02%20140932.png)

Запустим сервер командой python app.py  
[image4](https://github.com/vasiliza2/prog5_lr7/blob/b676d20c45a043e827089a71436d5bb1237364d3/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202024-11-02%20135314.png)![logo-OYJ34ERC](https://github.com/user-attachments/assets/c04058e3-ca08-4f95-869e-3fc2f8e8e61c)
