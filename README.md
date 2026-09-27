# 🚀 Global Update v2.0.0 — MikaruStart OS Shell

The project has been fully rewritten from scratch to turn your browser homepage into a minimalist, feature-rich PC OS shell. The entire project is now bundled into a **single standalone `index.html` file**, requires no build tools, and remains **100% AI-free** and offline.

---

## 🇺🇸 Change Log (English)

### 🌟 Key Features & Improvements:
* **📱 Smartphone Boot Animation:** Added an immersive startup screen. The system greets you by your custom username and dynamically detects your current browser via JavaScript (`navigator.userAgent`).
* **🧱 Bento Grid Architecture:** All widgets are now organized in a clean layout with `24px` border-radius, glassmorphism blur effects (`backdrop-filter: blur`), and signature red indicator dots.
* **🩹 Clean UI & Scrollbarless Design:** Fully removed the ugly default white system scrollbars from the `Quick Links` block (`scrollbar-width: none`). The link bars are thinner, and delete icons (crosses) are hidden by default, appearing only on hover.
* **🎵 Custom Audio Player:** Ambient background noises are completely gone. Replaced by a functional media player with an animated CSS visualizer and an input field to stream your own MP3 tracks or online radio feeds.
* **🌐 Native Dual Language (EN / RU):** Added instant language switching inside the settings without reloading the page.
* **⚙️ Advanced Settings Widget:** Control your layout locally! You can now change your username, toggle the Dot Matrix background grid, and switch background themes (Pure AMOLED Black / Textured Dark). Everything saves instantly via `localStorage`.
* **🎨 Designer Fonts & Open-Source Icons:** Integrated a perfect mix of web fonts (`VT323`, `Oi`, `Inter`) and modern minimal outline icons (Lucide / Phosphor Icons) instead of basic arrows.

---

## 🇷🇺 Список изменений (Russian)

### 🌟 Ключевые особенности и улучшения:
* **📱 Стартовая анимация смартфона:** Добавлена интерактивная загрузка при старте страницы. Система приветствует вас по имени и динамически определяет через JavaScript (`navigator.userAgent`), какой браузер вы сейчас используете.
* **🧱 Интерфейс Bento Grid:** Карточки получили скругления `border-radius: 24px`, эффект матового стекла (`backdrop-filter: blur`) и фирменные красные точки-индикаторные элементы.
* **🩹 Ультра-минимализм и скрытые скроллбары:** Полностью убраны стандартные системные белые полосы прокрутки в блоке быстрых ссылок (`Quick Links`). Плашки стали тоньше, а крестики удаления скрыты по умолчанию и появляются только при наведении (`:hover`).
* **🎵 Настраиваемый музыкальный плеер:** Старые фоновые шумы полностью удалены. Вместо них встроен полноценный аудио-плеер с кастомным визуализатором полосок и полем ввода, куда вы можете вставить ссылку на свой MP3-трек или любимое онлайн-радио.
* **🌐 Двуязычность (EN / RU):** В настройки добавлен переключатель языков. Весь интерфейс переводится мгновенно без перезагрузки страницы.
* **⚙️ Панель настроек:** Появился выезжающий виджет кастомизации. Можно менять имя пользователя, включать/выключать сетку фоновых точек (`Dot Matrix Background`) и переключать темы фона (Абсолютный AMOLED-черный или Текстурный). Все данные сохраняются в `localStorage`.
* **🎨 Премиум-шрифты и Open-Source иконки:** Интегрирован микс шрифтов (`VT323`, `Oi`, `Inter`) и минималистичные контурные дизайнерские значки вместо стандартных стрелок.

---

### 📦 Technical Stack / Технический стек:
* **Architecture:** 1 Single Single-File Component (`index.html`)
* **Fonts:** Google Fonts API
* **Icons:** Lucide / Phosphor Icons via CDN
* **Storage:** 100% Local Browser Storage (`localStorage API`)
