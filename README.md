# 💣 Сапёр / Minesweeper

Браузерная игра «Сапёр» в стиле ретро-терминала. Написана на чистом HTML/CSS/JavaScript — без зависимостей и сборщиков.

**[▶ Играть онлайн](https://padre_777.github.io/minesweeper/)**

![preview](https://img.shields.io/badge/HTML-CSS-JS-green?style=flat-square&logo=html5)
![license](https://img.shields.io/badge/license-MIT-green?style=flat-square)

---

## Возможности

- 3 уровня сложности: Лёгкий (9×9, 10 мин), Средний (16×16, 40 мин), Эксперт (16×30, 99 мин)
- Первый клик всегда безопасен — мины расставляются после него
- Chord-клик: кликни на цифру с нужным числом флагов рядом — откроются остальные клетки
- Таймер и счётчик оставшихся мин
- Анимации: взрыв, открытие клеток, мерцание экрана
- Работает полностью офлайн (нужен только Google Fonts для шрифтов)

## Управление

| Действие | Клавиша / кнопка |
|----------|-----------------|
| Открыть клетку | ЛКМ |
| Поставить / снять флаг | ПКМ |
| Chord-открытие | ЛКМ по цифре (если флаги расставлены) |
| Новая игра | Кнопка ↺ |

## Запуск локально

Просто открой `index.html` в браузере — никакого сервера не нужно.

```bash
git clone https://github.com/YOUR_USERNAME/minesweeper.git
cd minesweeper
# Открой index.html в браузере
```

## Публикация на GitHub Pages

1. Залей репозиторий на GitHub
2. Перейди в **Settings → Pages**
3. В разделе **Branch** выбери `main` и папку `/ (root)`
4. Нажми **Save** — через минуту игра будет доступна по адресу `https://YOUR_USERNAME.github.io/minesweeper/`

## Технологии

- Vanilla JavaScript (ES6+)
- CSS Custom Properties, Grid, анимации
- Шрифты: [Orbitron](https://fonts.google.com/specimen/Orbitron) + [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono) (Google Fonts)

## Лицензия

[MIT](LICENSE)
