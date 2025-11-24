# 👋 Привет, я Герман

Создаю удобные цифровые инструменты и люблю автоматизировать рутину. На этой странице собираю полезные виджеты, которые делают профиль живым и наглядным.

- 🔭 Сейчас развиваю pet‑проекты на TypeScript и Go
- 🧠 Изучаю низкоуровневую разработку и DevOps‑подходы
- 🌐 Всегда открыт к интересным open source инициативам
- 📫 Как связаться: [Telegram](https://t.me/6ermvH) • [Email](mailto:hi@6ermvh.dev)

## ⚙️ Технологии и инструменты

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=fff)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=fff)
![Node.js](https://img.shields.io/badge/Node.js-43853d?style=for-the-badge&logo=node.js&logoColor=fff)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=fff)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=fff)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=fff)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=fff)

> Все бейджи взяты с [shields.io](https://shields.io/) — можно менять цвета, иконки и стиль через параметры в URL.

## 📊 Немного статистики

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=6ermvH&theme=github_dark" alt="Общая активность" />
  <br />
  <img src="https://github-readme-stats.vercel.app/api?username=6ermvH&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=6ermvH&layout=compact&theme=tokyonight&hide=html,css&langs_count=8" alt="Top langs" />
  <br />
  <img src="https://streak-stats.demolab.com?user=6ermvH&theme=tokyonight-duo&date_format=j%20M%5B%20Y%5D" alt="GitHub streak" />
</div>

## 🧩 Расширения, которые обновляются автоматически

| Расширение | Что делает | Как добавить |
| --- | --- | --- |
| [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) | Карточки с репозиториями, языками и очками | Вставить markdown с `![...]` и ссылкой на сервис |
| [streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) | Visual streak по дням | Указать `user` и тему в URL |
| [profile-summary-cards](https://github.com/vn7n24fzkq/github-profile-summary-cards) | Несколько карточек с графиками | Задать `username` и выбрать тему |
| [metrics](https://github.com/lowlighter/metrics) | Генерирует огромные инфографики (прогресс, игры, активности) | Настроить GitHub Action, который раз в день обновляет `metrics.svg` |
| [waka-readme](https://github.com/athul/waka-readme) | Показывает статистику из WakaTime | Создать токен WakaTime, добавить в секреты репозитория и запускать Action |

## 🚀 Автоматизация

```yaml
name: Update dynamic widgets

on:
  schedule:
    - cron: "0 7 * * *"
  workflow_dispatch:

jobs:
  metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          filename: metrics.svg
          token: ${{ secrets.METRICS_TOKEN }}
          base: header, activity, community, repositories, metadata
          config_timezone: Europe/Moscow
```

Добавь подобный workflow в `.github/workflows/metrics.yml`, чтобы карточки всегда были актуальными. Токены (`METRICS_TOKEN`, `WAKATIME_API_KEY` и т.д.) сохраняются в `Settings → Secrets and variables → Actions`.

## 📌 Чем занимаюсь

- Разрабатываю полезные CLI‑утилиты и инструменты для разработчиков
- Пишу заметки о продуктивности и инфраструктуре
- Тестирую новые форматы визуализации в README и делюсь шаблонами

## 🤝 Хочешь пообщаться?

<a href="mailto:hi@6ermvh.dev"><img src="https://img.shields.io/badge/Email-hi%406ermvh.dev-orange?style=for-the-badge&logo=minutemailer&logoColor=white" /></a>
<a href="https://t.me/6ermvH"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a>

<br />

> ⭐️ Если что‑то понравилось — смело ставь звезду репозиторию или открывай issue с идеями по улучшению профиля.
