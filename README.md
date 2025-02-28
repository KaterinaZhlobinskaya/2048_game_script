# 2048 Game

Це реалізація популярної гри **2048**, створеної за допомогою JavaScript, HTML та CSS. Гра дозволяє гравцям з'єднувати плитки з однаковими числами, щоб досягти результату 2048.

## 📖 Про проєкт

У рамках цього проєкту я реалізувала функціональну логіку гри **2048**, зокрема генерацію плиток, їх об'єднання, переміщення та підрахунок балів. Гра автоматично завершується, якщо більше неможливо здійснити хід. Також передбачено базові стилі та інтерактивність для покращення користувацького досвіду.

## 🔧 Використані технології

- **HTML5**: базова структура гри.
- **CSS3**: стилізація ігрового поля та плиток.
- **Vanilla JavaScript**: реалізація основної логіки гри, включаючи:
  - Генерацію нових плиток.
  - Перевірку можливих ходів.
  - Підрахунок очок.
  - Завершення гри.

## 🕹 Основний функціонал

1. **Ігрове поле**:
   - Поле розміром 4x4.
   - Початкова генерація плиток з числами 2 або 4 у випадкових місцях.
2. **Рух плиток**:
   - Використання клавіш-стрілок для переміщення плиток.
   - Автоматичне об'єднання плиток однакових чисел.
   - Генерація нової плитки після кожного ходу.
3. **Перемога та завершення гри**:
   - Виграш при досягненні плитки з числом 2048.
   - Повідомлення про програш, якщо більше неможливо здійснити хід.
4. **Підрахунок балів**:
   - Сума балів збільшується залежно від значень об'єднаних плиток.

## ✨ Особливості

- **Реалізація ігрової логіки з нуля**: усі алгоритми (об'єднання, рух, перевірка стану гри) написані вручну.
- **Інтерактивний досвід**: гра плавно реагує на дії гравця, забезпечуючи зручність гри.
- **Адаптивний дизайн**: ігрове поле та плитки виглядають гармонійно на різних екранах.

## 🚀 Як переглянути проєкт

- Гра доступна за посиланням: [2048 Game](https://katerinazhlobinskaya.github.io/2048_game_script/).

## 🛠 Як запустити локально

- **Клонуйте репозиторій**:
     ```sh
     git clone https://github.com/KaterinaZhlobinskaya/2048_game_script.git
- **Відкрийте проєкт в редакторі коду** (приклад для VSC):
     ```sh
     code 2048_game_script
- **Перевірте версію ноди** (14.14.35 або вище):
  
       node -v
   - якщо версія не підходить до вимог, змініть її:
       ```sh
       nvm use XX.X.X
   - за відсутності встановленої Node встановіть її згідно інструкцій за посиланням:
       ```sh
       https://nodejs.org/uk/download
- **Встановіть залежності** (введіть наступну команду в терміналі редактора коду):
     ```sh
     npm install
- **Запустіть проєкт**:
     ```sh
     npm start

## 🛠 Чого я навчилася

- Роботи з DOM: динамічне створення та оновлення елементів сторінки.
- Побудови логіки гри та обробки користувацьких подій (клавіатура).
- Оптимізації JavaScript-коду для коректної роботи ігрових механік.
- Використання CSS для створення стильного інтерфейсу гри.

##

# 2048 Game

This is an implementation of the popular game **2048**, built using JavaScript, HTML, and CSS. The game allows players to connect tiles with the same numbers to achieve a score of 2048.

## 📖 About the project

In this project, I implemented the functional logic of the game **2048**, including tile generation, merging, moving, and scoring. The game automatically ends if no more moves can be made. Basic styles and interactivity are also provided to improve the user experience.

## 🔧 Technologies used

- **HTML5**: basic game structure.
- **CSS3**: stylization of the playing field and tiles.
- **Vanilla JavaScript**: implementation of the main game logic, including:
- Generating new tiles.
- Checking possible moves.
- Scoring.
- Ending the game.

## 🕹 Main functionality

1. **Playing field**:
- 4x4 field.
- Initial generation of tiles with numbers 2 or 4 in random places.
2. **Tile movement**:
- Use arrow keys to move tiles.
- Automatic merging of tiles with the same numbers.
- Generation of a new tile after each move.
3. **Winning and ending the game**:
- Winning when reaching the tile with the number 2048.
- Notification of loss if it is no longer possible to make a move.
4. **Scoring**:
- The sum of points increases depending on the values ​​of the merged tiles.

## ✨ Features

- **Implementation of game logic from scratch**: all algorithms (merging, movement, checking the game state) are written manually.
- **Interactive experience**: the game smoothly responds to player actions, ensuring a comfortable game experience.
- **Responsive design**: the playing field and tiles look harmonious on different screens.

## 🚀 How to view the project

- The game is available at the link: [2048 Game](https://katerinazhlobinskaya.github.io/2048_game_script/).

## 🛠 How to run locally

- **Clone the repository**:
     ```sh
     git clone https://github.com/KaterinaZhlobinskaya/2048_game_script.git
- **Open the project in the code editor** (example for VSC):
     ```sh
     code 2048_game_script
- **Check the node version** (14.14.35 or higher):
   
         node -v
   - if the version does not meet the requirements, change it:
       ```sh
       nvm use XX.X.X
   - if Node is not installed, install it according to the instructions at the link:
       ```sh
       https://nodejs.org/uk/download
- **Install dependencies** (enter the following command in the code editor terminal):
     ```sh
     npm install
- **Run the project**:
     ```sh
     npm start

## 🛠 What I learned

- Working with DOM: dynamically creating and updating page elements.
- Building game logic and handling user events (keyboard).
- Optimizing JavaScript code for correct operation of game mechanics.
- Using CSS to create a stylish game interface.
