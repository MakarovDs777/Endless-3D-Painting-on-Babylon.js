# Endless-Painting-on-Babylon.js

Нашел в Babylon.search рисовалку на невидимой плсокости [test painting | Babylon.js Playground](https://playground.babylonjs.com/#W8C73X#1) не знаю автора но я решил развить эту идею, и дальше, и создать бесконечную рисовалку вот что получилось в итоге:

Не нашел - создал! Бесконечная процедурно генерируемая плоскость для рисования.

[Endless painting (version 0) | Babylon.js Playground](http://playground.babylonjs.com/#T63RE2#0)

Но теперь нужно исправить курсор что-бы при рисование на плоскости не было зеркального дублирования нарисованого рисунка общего рисования.

[Endless painting (version 1) | Babylon.js Playground](https://playground.babylonjs.com/#J3V6QG#0)

Но курсор какой-то пьяный надо его починить.

[Endless painting (version 2 - fixed cursor) | Babylon.js Playground](https://playground.babylonjs.com/#1TNB7E#0)

Теперь нужно отменить дублирование рисование на все плоскости а сделать только одно рисование свободное.

[Endless painting (version 3 - Endless drawing map without mirroring) | Babylon.js Playground](https://playground.babylonjs.com/#FN1IF4#0)

Добавим таймер для автоматического стирания рисунка через определенные время.

[Endless painting (version 4 - The version with the timer of automatic auto-erasing of a drawing) | Babylon.js Playground](https://playground.babylonjs.com/#NIHXIP#0)

Теперь нужно добавить круг RGB для смены цвета кисти рисовалки.

[Endless painting (version 5 - Endless color drawing map without mirroring) | Babylon.js Playground](https://playground.babylonjs.com/#CLZPCV#0)

Теперь нужно убрать что-бы цвет плоскости менялся при смене цвета рисования.

[Endless painting (version 6 - Endless color drawing map without mirroring fixed version) | Babylon.js Playground](https://playground.babylonjs.com/#J6AMKX#0)

Но не удобно одновремено менять позиции камеры, и рисовать нужно сделать позицию камеры остановленной при рисование.

[Endless Painting (version 7 - Endless color drawing when you draw cameras fixed) | Babylon.js Playground](https://playground.babylonjs.com/#70VPXV#0)

Ну всё мы получили бесконечую рисовалку осталось лишь внести финальный штрих ввиде автоматического художника который пытается случайно рисовать точками красок на бесконечной процедурной плоскости.

[Endless Painting (version 8 - Endless automatic dot drawing) | Babylon.js Playground](https://playground.babylonjs.com/#YP47CQ#0)

Уберем точки сделем линии случайной длины отрезка, и случайных траекторий.

[Endless Painting (version 9 - Endless automatic random line drawing) | Babylon.js Playground](https://playground.babylonjs.com/#CEJLT7#1)

Ну вот и всё! Предлагайте ваши дальнейшие идеии в дискуссиях. И я спрограммирую.
