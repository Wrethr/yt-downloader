# 📼 Youtube Video Downloader

![Zig Version](https://img.shields.io/badge/Zig-0.15.2-orange?logo=zig&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-black)
![Style](https://img.shields.io/badge/Design-Minimalist-white)

Легковесный и быстрый инструмент для скачивания видео с YouTube, построенный на производительном языке **Zig**. Проект объединяет мощь `yt-dlp` с простым и эстетичным веб-интерфейсом.

---

## ✨ Особенности

* **Minimalist Aesthetic**: Чистое черно-белое оформление. Ничего лишнего, только фокус на контенте.
* **High Performance**: Бекенд на **Zig** обеспечивает мгновенную обработку запросов и минимальное потребление ресурсов.
* **Decoupled Architecture**: Логика сервера, HTML, CSS и JS разделены для удобной модификации.
* **Full Control**: Прямая интеграция с `yt-dlp` для максимальной стабильности.

## 🛠 Технологический стек

* **Язык**: [Zig 0.15.2](https://ziglang.org/)
* **Ядро загрузки**: [yt-dlp](https://github.com/yt-dlp/yt-dlp)
* **Обработка медиа**: [ffmpeg](https://ffmpeg.org/)

---

## 🚀 Быстрый старт

### Для пользователей (Release)
1. Скачайте последнюю версию во вкладке **[Releases](https://github.com/dimonc1o/Youtube-video-downloader/releases)**.
2. Распакуйте архив в удобную папку.
3. Убедитесь, что `yt-dlp` и `ffmpeg` установлены в вашей системе (или находятся в папке с программой).
4. Запустите исполняемый файл.
5. Откройте браузер: `http://127.0.0.1:8080`

### Для разработчиков (Сборка из исходников)
```bash
# Клонируйте репозиторий
git clone [https://github.com/dimonc1o/Youtube-video-downloader.git](https://github.com/dimonc1o/Youtube-video-downloader.git)

# Перейдите в папку проекта
cd Youtube-video-downloader

# Соберите проект с помощью Zig
zig build-exe main.zig
