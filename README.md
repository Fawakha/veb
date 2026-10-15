# 🎮 PEACH Gaming Ecosystem — Web Platform

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub_Pages-22c55e?style=for-the-badge&logo=github)](https://dmytro-salo.github.io/peach-gaming-platform/)
[![Netlify Status](https://img.shields.io/badge/Deploy-Netlify-00ad9f?style=for-the-badge&logo=netlify)](https://peach-gaming-landing.netlify.app)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3.4_JIT-38bdf8?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![HTML5 / W3C](https://img.shields.io/badge/HTML5-W3C_Valid-e34f26?style=for-the-badge&logo=html5)](https://validator.w3.org/)
[![Lighthouse](https://img.shields.io/badge/Lighthouse-100%25_a11y-f59e0b?style=for-the-badge&logo=lighthouse)](https://developer.chrome.com/docs/lighthouse)

Сучасний, адаптивний веблендинг для геймерської екосистеми **PEACH**, розроблений у межах курсу **«Технології веброзробки та дизайну»** (Лабораторні роботи №6, №7, №8). Платформа поєднує функціонал пошуку тімейтів без токсичності (Smart LFG), перегляд 4K кліпів, моніторинг ігрових серверів та офлайн кібер-хаб у Львові.

---

## 📌 Основний функціонал
- **Mobile-First Адаптивність:** Оптимізована під мобільні пристрої (375px), планшети (768px) та широкоформатні екрани (1440px).
- **Zero Toxicity LFG:** Інтерактивний Party Finder для пошуку напарників у Counter-Strike 2, Valorant, Apex Legends та Dota 2.
- **Мультимедіа та Ембеддинг:**
  - Вбудоване адаптивне промо-відео через YouTube `<iframe>` (`aspect-video`, `loading="lazy"`).
  - Інтерактивна карта Google Maps із геолокацією кіберспортивного хабу PEACH у Львові (вул. Степана Бандери, 12).
- **Live Server Informer:** Моніторинг статусу та затримки ігрових серверів (Київ, Варшава, Франкфурт, Стокгольм).
- **FAQ Акордеон:** Інтерактивний блок питань та відповідей на чистому JavaScript.

---

## 🛠 Стек технологій
- **Розмітка:** Семантичний HTML5 (теги `<header>`, `<main>`, `<section>`, `<footer>`, без div-soup).
- **Стилізація:** Tailwind CSS v3.4 JIT Engine + кастомні стилі `custom-styles.css` (шрифти Inter/Raleway, темний скролбар, neon glow).
- **Іконки:** Font Awesome 6.6.0.
- **Контроль версій:** Git, GitHub (Conventional Commits, Branching & Merging).
- **Деплой & Хостинг:** GitHub Pages, Netlify CI/CD.

---

## 📂 Структура репозиторію
```text
peach-gaming-platform/
├── assets/
│   ├── fonts/          # Локальні шрифти WOFF2 (Inter, Raleway)
│   ├── icons/          # Векторні SVG-іконки (favicon, logo)
│   └── images/         # Графічні ассети та SVG-ілюстрації
├── css/
│   ├── custom-styles.css # Кастомні стилі, змінні, анімації
│   └── style.css       # Базові резервні стилі
├── index.html          # Головна сторінка лендингу
├── netlify.toml        # Конфігурація заголовків безпеки для Netlify
├── .gitignore          # Правила ігнорування системних файлів
└── README.md           # Документація проєкту
```

---

## 🚀 Інструкція із локального запуску

1. Клонувати репозиторій на свій комп'ютер:
   ```bash
   git clone https://github.com/dmytro-salo/peach-gaming-platform.git
   cd peach-gaming-platform
   ```
2. Відкрити проєкт у Visual Studio Code:
   ```bash
   code .
   ```
3. Запустити локальний сервер за допомогою розширення **Live Server** (порт `5500`) або відкрити файл `index.html` у будь-якому сучасному браузері.

---

## 🌐 Посилання на живий сайт
- **GitHub Pages:** [https://dmytro-salo.github.io/peach-gaming-platform/](https://dmytro-salo.github.io/peach-gaming-platform/)
- **Netlify:** [https://peach-gaming-landing.netlify.app](https://peach-gaming-landing.netlify.app)

---

## 👤 Автор
- **Студент:** Сало Дмитро
- **Група:** ПП-24, Національний університет «Львівська політехніка»
- **Викладач:** Юрчак І.Ю.
