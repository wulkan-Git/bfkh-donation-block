# 🎗️ Блок пожертвований для Фонда Константина Хабенскогоn

![BFKH Donation Block](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success)
![HTML5](https://img.shields.io/badge/HTML5-✓-orange)
![CSS3](https://img.shields.io/badge/CSS3-✓-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-✓-yellow)

Адаптивный HTML-блок для размещения на сайтах с кнопкой пожертвований в Благотворительный Фонд Константина Хабенского.

## ✨ Демо

[Посмотреть живую демонстрацию](https://wulkan-git.github.io/bfkh-donation-block/) | [Скачать архив](https://github.com/wulkan-Git/bfkh-donation-block/archive/refs/heads/main.zip)

![Скриншот блока](screenshot.png)

## 🚀 Быстрый старт

### Вариант 1: Простое копирование (рекомендуется)

1. Скопируйте содержимое файла `index.html`
2. Вставьте в нужное место на вашем сайте
3. Готово!

### Вариант 2: Для WordPress

1. Создайте новую страницу/пост или отредактируйте существующий
2. Переключитесь в режим HTML/кода
3. Вставьте скопированный код
4. Сохраните изменения

### Вариант 3: Для статических сайтов

```html
<!-- Вставьте этот код в нужное место на странице -->
<div id="bfkh-donation-block-container"></div>

<script>
  fetch('https://raw.githubusercontent.com/wulkan-Git/bfkh-donation-block/main/index.html')
    .then(response => response.text())
    .then(html => {
      document.getElementById('bfkh-donation-block-container').innerHTML = html;
    });
</script>
