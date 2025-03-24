# .JACK CASINO
Наша игра создана на языке JACK в рамках проекта по nand2tetris.
## Возможности
В игре представленны несколько режимов игры:
* Однорукий бандит
    + Слоты с кастомными иконками. Легчайший способ проиграть деньги.
* Блэкджэк
    + Классический блэкджэк. Перед игрой необходимо перетусовать колоду (делайте это как в реальной жизни максимально случайно, т.е. жмите SPACE максимально случайно).
* Рулетка
    + Рулетка с возможностью выбора цвета для ставки (Если Никита ее доделает ;)))))) ).
## Как запустить игру?
1. Скачайте .zip и распакуйте его в любое удобное место.
2. Запустите VMEmulator.bat.
3. Нажмите кнопку Load Program в левом верхнем углу программы.
4. Найдите распакованную папку и выберите в ней папку vm.
5. Нажмите кнопку Load Program в правом нижнем углу открытого окна.
6. Сверху, посередине экрана в селекторе Animate: выберите No animation.
7. Запустите игру, нажав на кнопку >> (две синих стрелочки влево).
8. Наслаждайтесь!
## Изображения
Геймплэй однорукого бандита

![Геймплэй однорукого бандита](https://i.postimg.cc/fyKMNyG7/Bandit.png)

Геймплэй блэкджка

![Геймплэй блэкджэка](https://i.postimg.cc/tCB9v1tp/Blackjack.png)
## Для тех, кто не умеет играть в Блэкджэк
Каждая карта имеет свои очки, зависящие от ее номинала, масть ни на что не влияет.
Цель игрока - набрать 21 очко (или 22 если сразу получил 2 туза).
Очки карт:
* J (Валет) = 2 очка
* Q (Дама) = 3 очка
* K (Король) = 4 очка
* А (Туз) = 11 очков
* Остальные карты дают столько очков, сколько на них написано.
## Как реализован рандом?
В игре используется линейный конгруэнтный метод. Значение seed`а для него генерируется в нескольких циклах, пока ожидается пользовательский ввод.
## Полезные вещь при разработке на jack`е
В проекте есть файл build.ps1 который компилирует все файлы в папке src и перемещает их в папку vm. Можно использовать его и в других проектах.
### CREDITS
* [NikitaLi228](https://t.me/Nmnmm45)
* [Weller26](https://t.me/IlyaMironov26)
* [br41nd34d](https://t.me/br41nd34dd)