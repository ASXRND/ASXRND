# ASX

**macOS / iOS developer.** Пишу локальные инструменты для разработчика: нативные приложения на Swift,
утилиты на TypeScript/Python, интеграции с LLM и агентами.

Последние два года — про то, чтобы инструменты работали быстро и без облака:
один процесс, ноль подписок, данные лежат рядом с проектом.

---

## Что делаю сейчас

| Проект | Что это |
|---|---|
| **[canvas_asx](https://github.com/ASXRND/canvas_asx)** | Лёгкий канвас для macOS: бесконечная доска, живые терминалы (SwiftTerm + PTY), `.md`-заметки, файловая плитка с SSH/SFTP. Нативный SwiftUI, без Electron и WebView. |
| **[filecommander](https://github.com/ASXRND/filecommander)** | Двухпанельный файловый менеджер на SwiftUI: вкладки, сплиты, дерево, свойства, серверы через системный `ssh`/`scp`. Ноль зависимостей, 1.7 МБ. |

## Стек

**Нативно (macOS / iOS)**
Swift, SwiftUI, AppKit, SwiftPM · терминалы и PTY, ScreenCaptureKit-подходы, работа с окнами
и меню, NSDocument/файловые API · ранее — UIKit, CoreAnimation, Firebase (iOS-проекты в архиве ниже)

**Сервер и данные**
TypeScript, Node.js, Python · Django, REST-интеграции (маркетплейсы, аналитика, отчётность),
SQL, обработка данных и сигналов

**Инструменты вокруг LLM**
MCP-серверы, локальный инференс (llama.cpp), агентные пайплайны, консольные ассистенты

**Инфраструктура**
macOS, Linux, git, Docker, ssh · сборка и упаковка нативных приложений, подпись, диагностика

## Избранное

| Репозиторий | Стек | О чём |
|---|---|---|
| [MCP_deepseek](https://github.com/ASXRND/MCP_deepseek) | Python | MCP-сервер: доступ агентов к модели через локальный протокол |
| [console_deepseek_chat](https://github.com/ASXRND/console_deepseek_chat) | Python | Консольный чат с LLM без веб-интерфейса |
| [crypto-Signal](https://github.com/ASXRND/crypto-Signal) | Python | Расчёт торговых сигналов и оповещения |
| [oz_api](https://github.com/ASXRND/oz_api) · [reviews_wb](https://github.com/ASXRND/reviews_wb) | Python | Интеграции с API маркетплейсов: товары, отзывы, отчёты |
| [new_ecom_project_next](https://github.com/ASXRND/new_ecom_project_next) | TypeScript / Next.js | Магазин: каталог, корзина, заказы, админка |

<details>
<summary><b>Архив: iOS-проекты (2023, обучение)</b></summary>

| Проект | Что внутри |
|---|---|
| [FirebaseChat](https://github.com/ASXRND/FirebaseChat) | Чат на Firebase: авторизация, сообщения в реальном времени |
| [MyHabits](https://github.com/ASXRND/MyHabits) | Трекер привычек: UIKit, UICollectionView, UserDefaults |
| [Animations](https://github.com/ASXRND/Animations) | CoreGraphics / CoreAnimation: анимации интерфейса |
| [Weather-App](https://github.com/ASXRND/Weather-App) | Сеть, JSON, отображение прогноза |
| [ios-homeworks](https://github.com/ASXRND/ios-homeworks) | Домашние работы курса iOS |

<img src="https://github.com/ASXRND/ASXRND/blob/test/GifProject/FirebaseChatGif/1.gif" width="150">
<img src="https://github.com/ASXRND/ASXRND/blob/test/GifProject/MyHabitsGif/1.gif" width="150">
<img src="https://github.com/ASXRND/ASXRND/blob/test/GifProject/NavigationGif/1.gif" width="150">

</details>

---

Открыт к задачам, где нужен нативный macOS-клиент, терминальные/агентные инструменты
или интеграции с внешними API. Связаться — через issues в нужном репозитории.
