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

## 🛠 Чого я навчилася

- Роботи з DOM: динамічне створення та оновлення елементів сторінки.
- Побудови логіки гри та обробки користувацьких подій (клавіатура).
- Оптимізації JavaScript-коду для коректної роботи ігрових механік.
- Використання CSS для створення стильного інтерфейсу гри.
