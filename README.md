# Verification Code Card

Форма верификации с 4 полями для ввода кода. Реализована на ванильном JS и CSS.

## Функционал

- Автопереход между полями при вводе
- Копирование кода из буфера обмена во все поля
- Навигация стрелками и удаление Backspace
- Подсветка активного поля

## Технологии

**HTML5**: Семантическая разметка, `inputmode="numeric"`, `maxlength="1"`

**CSS3**: 
- Flexbox для верстки
- Box-shadow для неоморфизма карточки
- CSS анимации для shimmer-эффекта
- CSS анимации через keyframes
- Псевдоэлементы `::after` для кнопок
- Transitions для плавных переходов

**Vanilla JavaScript**:
- `addEventListener` для событий ввода
- Регулярки `/\D/g` для фильтрации чисел
- Clipboard API для paste
- Управление фокусом через `.focus()`

## Деплой

🌐 [Посмотреть проект](what-verification.vercel.app)
[what-verification.vercel.app]

## Структура

- `index.html` — разметка
- `script.js` — логика полей ввода
- `style.css` — макет и кнопки
- `input.css` — стили инпутов
- `text.info.p.css` — shimmer анимация

