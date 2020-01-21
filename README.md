# ВНИЗ! (пояснительная_записка.doc)
## Видео: <i>https://youtu.be/OIioynOaD6Q</i>
## Установка pybox2d: <i>https://github.com/pybox2d/pybox2d/blob/master/INSTALL.md</i>
## Запуск через командную строку: <i>python main.py</i>

**Автор:**

Тамбовцев Илья

**Суть игры:**

Пролететь как можно
больше уровней ВНИЗ.
Больше уровней - больше очков

Для этого сделано
- Создан &quot;мир&quot; в котором происходят все действия
- Добавлены два вида препятствий: шипы и пилы
- Реализована динамика игры

**Реализация:**

1)  Использованы библиотеки:
- pygame
- pybox2d
- random

2) Классы _Player, Eraser, Ball_ реализуют игру со стороны пользователя

3) Классы _Spikes, Blade_ - препятствия. То, что убивает игрока.

4) Класс _ObstacleManager_ отвечает за расстановку препятствий на игровом поле

**Из приёмов:**

-  Использование сторонней библиотеки **pybox2d**
-  Каждый уровень &quot;вновинку&quot;. Уровней 30 но каждый раз они выглядят по-новому

**Как играть:**
###### За что очки?
- +2 за пилу
- +1 за шипы

Рисуем на ПКМ

Стираем на ЛКМ
