# Игра "Догони меня если сможешь" с интегрированным меню
## 1. Описание функций
### Функция set status: должна задавать вид текста. К примеру, если включено меню, текст должен быть соответствующим. Функция key handler должна передвигать персонажей игры вправо на константу SPEED (о ней позже). Функция check finish должна завершить игру при достижении одного из персонажей финишной линии
## 2. Описание переменных
### Константа SPEED равна 12, задаёт скорость движения персонажа. game_width и game_height равны 800 и задают размер экрана. player_size = 150, player1_color задаёт красный цвет первому игроку, player2_color синий второму. KEY_PLAYER1 = 39, KEY_PLAYER2 = 68, gameover = False