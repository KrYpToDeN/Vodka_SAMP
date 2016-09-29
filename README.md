# Advanced-SA-NickName v4.0 - Русские ники в SAMP.
Особенность данного плагина заключается в следующем:

1. Вам не нужно изменять адреса памяти при переходе на новую версию SA:MP сервера. Плагин всё сам сделает за Вас.
2. Любые манипуляции с плагинов происходят в файле конфигураций scriptfiles/ASAN.ini (создается при первом запуске)
3. В версии 4.0 вы сами устанавливаете длину ника и правила разрешенных символов через регулярные выражения (Regex). Прошлые версии плагина работают без Regex.
4. С помощью Regex Вы можете настроить плагин, сделав недоступным использования в нике одновременно Русских и Английских символов.
5. Плагин не только сам ищет адрес памяти, но и умеет определять версию сервера, не зависимо от названия файла запуска сервера.
5. Обязательно подключите инклуд в мод, чтобы связать плагин и мод, а также иметь возможность использовать дополнительные функции плагина(функция IsValidNickName(name[])).
6. Большая и убедительная просьба. ПРОЧИТАЙТЕ инструкцию, которая прилагается в архиве.
7. На данный момент багов не обнаружено!

Лог изменений + инструкция Вы можете увидеть в Архиве.

--
Для компиляции:

1. На Windows используйте Visual Studio (желательно не ниже 2015 года).
2. На Linux используйте GCC не ниже 4.9 версии. Иначе Вы не сможете работать с Regex.

Спасибо за использования.
С Уважением, [KrYpToDeN] | Skype - kryptoden
