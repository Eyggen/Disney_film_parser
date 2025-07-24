# 🎬 Disney Film Parser

A Python web scraping tool to extract structured data about Disney movies (e.g., title, year, genre, director, budget, box office) from reliable online sources and export it in CSV or JSON format.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Options](#options)
- [Example Output](#example-output)
- [Project Structure](#project-structure)
- [Technology Stack](#technology-stack)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 Overview
**Disney Film Parser** — це легко налаштований парсер, який автоматично:
- збирає назви фільмів студії Disney,
- витягує ключові метадані (рік, жанр, режисер, бюджет, каса),
- зберігає результати в структурованому вигляді для подальшого аналізу, візуалізації або машинного навчання.

---

## ✨ Features
- **Парсинг** з авторитетних веб-сайтів (Wikipedia/IMDb)
- **Фільтрація** за роками (від–до)
- **Множинні формати виводу**: CSV та JSON
- **CLI–інтерфейс** з аргументами командного рядка
- **Модульна структура** — легко додавати нові джерела або поля

---

## 🛠️ Installation

1. Клонувати репозиторій:
    ```bash
    git clone https://github.com/Eyggen/Disney_film_parser.git
    cd Disney_film_parser
    ```
2. Встановити залежності:
    ```bash
    pip install -r requirements.txt
    ```

---

## 🚀 Usage

### Базовий запуск:
```bash
python parser.py
