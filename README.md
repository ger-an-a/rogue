## Пошаговая Игра "РОГАЛИК" на JavaScript (Тестовое задание).

### [ИГРАТЬ ЗДЕСЬ.](https://ger-an-a.github.io/rogue/)

### Текст задания: 
Исходные данные: Архив с html, css, jquery и картинками

#### Задачи:
- Сгенерировать случайную карту;
- Залить всю карту стеной;
- Разместить случайное количество (5 - 10) прямоугольных “комнат” со случайными размерами (3 - 8 клеток в длину и ширину);
- Разместить случайное количество (3 - 5 по каждому направлению) вертикальных и горизонтальных проходов шириной в 1 клетку;
- Разместить мечи (2 шт) и зелья здоровья (10 шт) в пустых местах;
- Поместить героя в случайное пустое место;
- Поместить 10 противников с случайные пустые места;
- Сделать возможность передвижения героя клавишами WASD (влево-вверх-вниз-вправо);
- Сделать возможность атаки клавишей пробел ВСЕХ противников находящихся на соседних клетках;
- Сделать атаку героя противником, если герой находится на соседней клетке с противником;
- Сделать случайное передвижение противников (на выбор, либо передвижение по одной случайной оси, либо случайное направление каждый ход, либо поиск и атака героя);
- Сделать восстановление здоровья при наступлении героя на зелье здоровья (и удаление зелья);
- Сделать увеличение силы удара героя при наступлении героя на меч (и удаление меча);

#### Условия:
- Должно запускаться открытием файла index.html в браузере (без сервера)
- Не должно быть недостижимых зон

#### Требования к коду:
- Отсутствие повторяющихся кусков, переиспользование кода там, где это возможно
- Хранение состояния внутри Javascript, а не в DOM
Можно сделать еще что-то на ваш выбор.


## Что добавлено от себя:
- Отображение начала и конца игры (выйгрыш - все противники убиты, проигрыш - герой убит);
- Начало игры по нажатию на любую кнопку ( добавлена задержка перед отслеживанием нажатия );
- В начале игры противники случайно выбирают режим движения: по оси Х, по оси Y либо в случайном направлении;
- При столкновении с препятствием (стена, зелье или меч) противних меняет направление, оставаясь на своей траектории;
- После нанесения урона герою противник начинает преследовать героя до первого препятствия по прямой траектории;
- После столкновения с препятствием при преследовании противник случайно выбирает новый режим движения;
- Меч увеличивает силу на определенное время;
- Эффекты от предметов и действия персонажей сопровождаются цветовой тенью/анимацией;
