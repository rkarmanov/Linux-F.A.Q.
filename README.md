# F.A.Q.

Q: Какой дистрибутив самый лучший?

A: Лучшего нет. Новичку рекомендуется начать с Mint, Ubuntu или OpenSuse.

Q: Какой дистрибутив самый быстрый?

А: Все примерно одинаковы. Можешь попробовать собрать/скомпиллировать [ПО](https://ru.wikipedia.org/wiki/Программное_обеспечение) или заменить стандартный [DE](https://ru.wikipedia.org/wiki/Среда_рабочего_стола) на более легковесный или же вовсе на [WM](https://ru.wikipedia.org/wiki/Менеджер_окон_X_Window_System). 

Q. Как писать по-русски?

A. Введи в терминал _setxkbmap -model pc105 -layout us,ru -option grp:alt_shift_toggle_. Теперь *alt+shift* переключает раскладку (варианты в `/usr/share/keymaps/i386/qwerty/ruwin_*`). Если не найдёшь в настройках DE, то добавь в автозагрузку.

Q: Могу ли я поставить Linux на EFI, рядом с виндой, на флешку, etc.

А: Да. Рекомендуемые дистрибутивы могут сделать это автоматически.

Q: Как разбить диск.

A: Автоматически 

Q: Нужен ли swap (фаил подкачки)
A: Да. 4Гб.

Q: На винде я пользовался <программа>, чем заменить?

A: http://alternativeto.net/. Если там нет необходимого, то попробуй в [wine](https://ru.wikipedia.org/wiki/Wine) или [виртуальной машине](https://ru.wikipedia.org/wiki/Виртуальная_машина).

Q: Что делать, если всё зависло?

A: Почитай про [magic SysRQ](https://ru.wikipedia.org/wiki/SysRq). Работает напрямую с ядром и выручит всегда.

Q: Нет звука, что делать?

A1: Скорее всего у тебя pulseaudio, тогда стоит открыть pavucontrol и посмотреть, какое устройство выводит звук

А2: Если pavucontrol отсутствует, вероятно, у вас alsa, тогда выполните alsamixer и убедитесь, что выбрано правильное устройство и нажмите “m”, если видите под графами “MM”.
