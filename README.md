**Matrix Dungeon. Дизайн-документ**

**Платформа:** Windows

**Технологии:** C#, Unity

**Язык:** Русский

**Жанр:** Образовательная игра

**Сеттинг:** Средневековое подземелье

**Сюжет.** Алхимик отправляется исследовать подземелье, чтобы найти философский камень. На его пути будут встречаться монстры, которых нужно победить и пройти на следующий уровень. 
Чтобы использовать заклинание на противнике, Алхимику нужно решить выражение с математической матрицей.

**Игровой мир.** Подземелье в мрачных тонах. 

**Геймплей.** В течение игры игроку нужно помогать Алхимику решать матрицы, с помощью которых тот использует заклинания и сражается с противниками. На каждом уровне предусмотрен свой тип задания с матрицей: 
1.	Сложение/вычитание матриц
2.	Транспонирование матрицы
3.	Определитель матрицы (3 на 3) 
4.	Умножение матриц
5.	Поиск обратной матрицы
6.	Поиск ранга матрицы
7.	Битва с боссом (большое матричное выражение)
 
На каждом уровне перед решением каждого задания игрок может прочитать небольшой диалог с Алхимиком, дающим подсказки для решения новых заданий, который погружает в сюжет происходящей игры. На каждом из уровней игроку
нужно три раза правильно решить задание, чтобы перейти к следующему уровню. Для этого у него есть три попытки (отображаются в здоровье на текущем уровне). Если все три были неудачными, он начинает проходить уровень заново,
то есть сбрасывается счетчик уже решенных заданий и здоровья. Если у игрока есть желание, он может остаться на текущем уровне и продолжить решать задания текущего типа, так как матрица для задания каждый раз генерируется случайным образом.
На каждом уровне есть подсказки для текущего типа заданий. В конце игры при удачном прохождении битвы с боссом игра оканчивается победой.

**Объекты:**
Матричное выражение;
Матрица для решения задания;
Матрица/поле для ввода ответа;
Кнопки для взаимодействия с игрой («играть», «следующий уровень», «проверить ответ», «повторить уровень», «показать подсказку», «следующая реплика диалога»);
Окно диалога персонажей.
