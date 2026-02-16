# FIGMA.PRO - Інформаційний портал про дизайн-платформу Figma

## Опис проекту

FIGMA.PRO - це сучасний освітній веб-сайт, присвячений вивченню Figma - професійного інструменту для UX/UI дизайну. Проект створено як дипломну роботу з використанням HTML5, CSS3 та JavaScript.

## Технології

- **HTML5** - семантична розмітка, валідний код
- **CSS3** - сучасні стилі, flexbox, grid, анімації, градієнти
- **JavaScript (ES6)** - інтерактивність, auto-hide header
- **Font Awesome 6.4** - іконки
- **YouTube API** - вбудовані відео

## Основні можливості

### Дизайн
- ✅ Неоморфізм та яскраві акценти (Acid Green, Hot Pink)
- ✅ Картковий стиль з обертанням елементів
- ✅ Контрастна темна/світла тематика
- ✅ Чорні границі та виразні тіні

### Адаптивність
- ✅ Повністю респонсивний дизайн
- ✅ Оптимізовано для мобільних пристроїв
- ✅ Медіа-запити для різних розмірів екранів
- ✅ Touch-friendly інтерфейс

### Інтерактивність
- ✅ Auto-hide header при скролі
- ✅ Плавні переходи та hover-ефекти
- ✅ Вбудовані YouTube відео
- ✅ Завантаження файлів проекту

## Структура сайту

```
/
├── index.html          # Головна сторінка
├── guide.html          # Повний гайд по роботі з Figma
├── history.html        # Історія Figma (2012-2024)
├── tech.html           # Технічна архітектура
├── tips.html           # PRO фішки та лайфхаки
├── project.html        # Матеріали проекту
├── style.css           # Основні стилі
├── script.js           # JavaScript функціонал
├── assets/
│   ├── img/            # Зображення та скріншоти
│   ├── files/          # Документи (PDF, DOCX, PPTX)
│   └── video/          # Відео контент
└── README.md           # Документація
```

## Контент

### Гайд (guide.html)
- Робочий простір Figma (Layers, Canvas, Inspector)
- Фрейми vs Групи
- Векторне редагування та Vector Networks
- Прототипування та анімації
- Вбудовані навчальні відео

### Історія (history.html)
- 2012: Початок, грант Тіля ($100,000)
- 2015: "Стелс" режим та технічні виклики
- 2016: Реліз та революція мультиплеєра
- 2022-2024: Угода з Adobe на $20 млрд та її провал

### Теорія (tech.html)
- WebAssembly та C++ рушій
- Vector Networks технологія
- CRDT алгоритми синхронізації
- Scene Graph та WebGL рендеринг

### Фішки (tips.html)
- Auto Layout (Shift + A)
- Компоненти та варіанти
- Гарячі клавіші (Ctrl+R, Shift+2, Ctrl+Alt+C/V)
- Absolute Position всередині Auto Layout

### Файли (project.html)
- Реферат (DOCX)
- Презентація (PPTX)
- Бюлетень (PDF)
- Модуль тестування (EXE)
- Інфографіка та відеоролик

## Особливості реалізації

### HTML5
- Семантичні теги (`header`, `footer`, `nav`, `main`)
- Валідна розмітка відповідно до стандартів W3C
- Meta-теги для SEO та адаптивності
- Вбудовані відео (YouTube iframe з privacy mode)

### CSS3
- CSS Grid та Flexbox для макетів
- CSS Variables для кольорової схеми (--acid-green, --hot-pink)
- Transform та transition для плавності
- Responsive design через media queries
- Кастомні картки з обертанням (rotate transform)

### JavaScript
- Vanilla JS (без фреймворків)
- Auto-hide header при скролі вниз
- Event listeners для взаємодії
- DOM маніпуляції
- Smooth scroll behavior

## Кольорова палітра

```css
--acid-green: #CCFF00;  /* #акцент */
--hot-pink: #FF006E;    /* #акцент2 */
--black: #000000;       /* #контури */
--white: #FFFFFF;       /* #фон */
```

## Сумісність

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Мобільні браузери (iOS Safari, Chrome Mobile)

## Валідація

Код пройшов валідацію:
- ✅ W3C HTML Validator
- ✅ W3C CSS Validator (Jigsaw)

## GitHub Pages

Сайт опубліковано на GitHub Pages:
**[Посилання буде додано після публікації]**
