# 🎬 Disney Film Parser

A Python web scraping tool to extract structured data about Disney movies (e.g., title, year, genre, director, budget, box office) from reliable online sources and export it in CSV or JSON format.

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
- **Модульна структура** — легко додавати нові джерела або поля

---

## 🛠️ Installation

1. Клонувати репозиторій:
    ```bash
    git clone https://github.com/Eyggen/Disney_film_parser.git
    cd Disney_film_parser
    ```
---
## 📦 Example Output

Here’s a preview of the parsed Disney movie data:

| Title                  | Release Date | Genre       | Total Gross   | Distributor                          |
|------------------------|--------------|-------------|---------------|--------------------------------------|
| Zootopia               | 2016-03-04   | Adventure   | $341,268,248  | Walt Disney Studios Motion Pictures |
| Zookeeper's Wife       | 2017-03-31   | Drama       | $17,476,330   | Focus Features                       |
| Your Friend the Rat    | 2007-11-06   | Documentary | $0            | Walt Disney Studios Motion Pictures |
| Young Black Stallion   | 2003-12-25   | Adventure   | $933,614      | Buena Vista                          |
| Yellowstone Cubs       | 1963-03-01   | Documentary | $0            | Buena Vista                          |


A sample of the exported dataset (`disney_movies_data_clean_final.csv`):

```csv
title,release_date,genre,mpaa_rating,total_gross,adjusted_total_gross,distributor,source,release_year
Zootopia,2016-03-04,Adventure,PG,341268248,395227218,Walt Disney Studios Motion Pictures,Original,2016
Zookeeper's Wife,2017-03-31,Drama,PG-13,17476330,18603248,Focus Features,Book,2017
Your Friend the Rat,2007-11-06,Documentary,G,0,0,Walt Disney Studios Motion Pictures,Original,2007
Young Black Stallion,2003-12-25,Adventure,G,933614,1381862,Buena Vista,Book,2003
Yellowstone Cubs,1963-03-01,Documentary,G,0,0,Buena Vista,Original,1963
```
Fields:

- title: Movie title

- release_date: Date of release (YYYY-MM-DD)

- genre: Genre (e.g., Adventure, Drama, Animation)

- mpaa_rating: MPAA age rating (e.g., G, PG, PG-13)

- total_gross: Total box office gross in USD

- adjusted_total_gross: Gross adjusted for inflation

- distributor: Movie distributor (e.g., Buena Vista, Walt Disney Studios)

- source: Story source (e.g., Original, Book, True Story)

- release_year: Year of release
