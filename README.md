# Чтобы настроить среду разработки на mac os Mojave тебе нужно выполнить пару шагов

## Пожалуйста прочти инструкцию от начала до конца. Если что-то кажется тебе сложным, отложи настройку или пройди по шагам виртуально не внося изменений, а когда будешь готов повтори шаг за шагом.

[Скачать и установить IDE PhpStorm](https://www.jetbrains.com/phpstorm/)

![](img/1.1.png)

---

Открыть терминал. (Mac > Aplications(Программы, если у тебя русский интерфейс) > Utilites(Утилиты)

![](img/1.2.png)

---

### Откроется такое окно:

![](img/1.3.png)

---

После знака $ скопируй и вставь следующую команду:

sudo nano /private/etc/apache2/httpd.conf

![](img/1.4.png)

---

и нажми клавишу «ввод»

Теперь нужно ввести пароль и нажать клавишу «ввод»

(во время ввода пароля в терминале ничего не происходит. Не обращай внимания. Это заморочки безопасности)

![](img/1.5.png)

---

Откроется файл httpd.conf

![](img/1.6.png)

---

Нужно найти строку: # LoadModule php7_module libexec/apache2/libphp7.so

Сделать это можно зажав клавиши «ctrl» и «W», вставить строку и нажать клавишу «ввод»

раскомментируй её удалив символ «#» из начала строки.

![](img/1.7.png)

---

Далее зажимаешь клавиши «ctrl» и «Х», 

подтверждаешь выход с сохранением измениений нажатием клавиши «Y» следом нажать клавишу «ввод»

Хорошо. Давай проверим как всё работает. Создай папку в удобном для тебя месте.

Запусти PhpStorm и открой созданную папку

![](img/1.8.png)

---

далее правый клик по папке - создать новый PHP файл. Назовём его index.php

![](img/1.9.png)

---

Далее настройки

![](img/1.13.png)

---

Сделай всё как на скриншоте:

![](img/1.14.png)

![](img/1.15.png)

---

Открой встроенный терминал

![](img/1.10.png)

---

Набери: php -S localhost:63342 и нажми клавишу «ввод»

![](img/1.11.png)

---

![](img/1.12.png)

---

Если ты увидел это - то всё правильно сделал

![](img/1.16.png)

Внеси изменения в файле

![](img/1.19.png)

Обнови браузер

![](img/1.18.png)

# Готово! поздравляю!

Далее Git. Система контроля версий так же встроена в PhpStorm.

Давай я тебе всё покажу.

![](img/1.20.png)

Клонирование репозитория. Залогинься, вставь ссылку на репозиторий, укажи путь до папки(она может лежать в где угодно, главное должна быть пустой)

![](img/1.22.png)

![](img/1.23.png)

![](img/1.24.png)

![](img/1.25.png)

---

[Про синхронизацию с удаленным сервером посмотри на YouTube](https://www.youtube.com/watch?v=ZKH7kIRyURY&list=PLY4rE9dstrJzAnXFt9m48Q0V5_2kVK1Qt)

[И ещё видео](https://www.youtube.com/watch?v=23VkWSKZ_lM&list=LL6qZ8UhL1_nPfu5C16YXlvA&index=2&t=0s)
