# Quiz
Quiz version1

# Quiz App Documentation

🌐 **Languages:** [English](#english-version) | [Русский](#russian-version)

---

<a id="english-version"></a>

## 🇬🇧 English

### Overview

A fully autonomous, single-file HTML/JS quiz application. Designed with a **mobile-first** approach but works flawlessly on desktop PCs. The app requires no external dependencies or internet connection to run.

### Key Features

- **Zero Dependencies**: Completely standalone HTML file. No CDNs, no external CSS/JS libraries. Works 100% offline.
- **Two Game Modes**:
  - **Training**: Infinite practice mode with a running score counter. Prevents the same question from appearing consecutively.
  - **Testing**: Fixed-length exam (default 6 questions) with unique questions, a progress bar, and a grading scale (1 to 5+).
- **Smart Prompting**: Randomly decides whether to show the *Question* or the *Answer* as the prompt, making the learning process more dynamic.
- **Visual Feedback**: Instantly highlights correct answers in green and incorrect ones in red (also revealing the correct answer if the user guessed wrong).
- **Customizable UI**: Real-time color pickers for text, background, and buttons, plus font size adjustment.
- **Persistent Settings**: All visual preferences are automatically saved to `localStorage` and restored on the next visit.
- **Adaptive Typography**: All font sizes are linked to a CSS variable, ensuring perfect scaling across all UI elements when the user adjusts the text size.
- **Easy Data Management**: Quiz data is stored in a clearly documented, easily editable JavaScript array (`quizData`) at the top of the `<script>` block.

### License

Licensed under the MIT License. Free to use, modify, and distribute with attribution.

---

<a id="russian-version"></a>

## 🇷🇺 Русский

### Обзор

Полностью автономное однофайловое HTML/JS приложение для проведения викторин. Разработано с подходом **mobile-first** (приоритет мобильной версии), но отлично адаптируется и работает на настольных ПК. Для работы не требует подключения к интернету или внешних библиотек.

### Ключевые особенности

- **Полная автономность**: Единый HTML-файл без внешних зависимостей. Не использует CDN, внешние CSS/JS библиотеки. Работает 100% офлайн.
- **Два режима работы**:
  - **Тренировка**: Бесконечный режим практики с текущим счетчиком правильных ответов. Алгоритм исключает повторение одного и того же вопроса подряд.
  - **Тестирование**: Фиксированный экзамен (по умолчанию 6 вопросов) без повторений, с прогресс-баром и системой оценивания (от 1 до 5+).
- **Умная генерация заданий**: Система случайным образом решает, что показать в качестве заголовка — *Вопрос* или *Ответ*, что делает процесс обучения более динамичным и вариативным.
- **Визуальная обратная связь**: Мгновенная подсветка правильных ответов зелёным цветом, а неправильных — красным (с обязательным указанием верного варианта).
- **Гибкая настройка интерфейса**: Интерактивные палитры (color pickers) для изменения цвета текста, фона и кнопок, а также кнопки для регулировки размера шрифта.
- **Сохранение настроек**: Все визуальные предпочтения пользователя автоматически сохраняются в `localStorage` и восстанавливаются при следующем запуске.
- **Адаптивная типографика**: Все размеры шрифтов жестко привязаны к CSS-переменной, что гарантирует идеальное масштабирование абсолютно всех элементов интерфейса при изменении размера текста.
- **Простое управление данными**: База вопросов и ответов хранится в отдельном, хорошо прокомментированном и легко редактируемом массиве JavaScript (`quizData`) в начале блока `<script>`.

### Лицензия

Лицензия MIT. Свободное использование, модификация и распространение с указанием авторства.
