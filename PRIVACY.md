# Polymosta — Privacy Policy

*Last updated: 8 November 2026. Русская версия — ниже.*

Polymosta is a free language-learning app for Windows, Linux and Android. It has no accounts, no advertising, no analytics and no tracking. The developers run no server that receives your data.

## Data that stays on your device

- **Your learning data** — profile (languages, levels, goal), words, notes, books, playlists and progress — is stored as Markdown files in a folder on your device (on Android: `Documents/Polymosta` or the app's private storage). You can open, copy or delete it at any time.
- **Settings and API keys** you enter for AI or translation services are stored only on the device and never written to the data folder.
- **Microphone** (pronunciation practice): audio is recorded only while you press the button and is recognised on the device. It is never uploaded.
- **Camera, photos and screenshots** (text recognition): images are processed on the device and never uploaded.
- **Offline dictionaries** are stored on the device.
- **Progress files** you save stay wherever you put them. Polymosta doesn't send them anywhere.
- **MCP** (PC, off unless you set it up): a program you connect this way can read your data folder and add words to it.

## Data that leaves your device — only when you use a feature that needs it

| Feature | What is sent | Where |
| --- | --- | --- |
| AI features (word drafts, explanations, stories, translation of book pages, picking words from a text, notes) | The text of the request: the words or text you are working on, your languages, levels and learning goal | The AI provider selected in Settings → AI. By default OVHcloud AI Endpoints (servers in France, oai.endpoints.kepler.ai.cloud.ovh.net); alternatively any provider listed there, or a model on your own computer (LM Studio, Ollama) |
| Translation without AI | The word or text to translate (and an e-mail address only if you enter one for MyMemory) | The translator selected in Settings → Translator: MyMemory (default), Apertium, Google Cloud Translation, Microsoft Translator, DeepL, LibreTranslate (a server you specify), ModernMT, Yandex Translate, Baidu, NiuTrans, Youdao, Papago or Sarvam. With a key, the provider’s own privacy policy applies |
| Lessons and exams | The topic, your answers to writing tasks, and, if you choose it, passages from your own book or file | The AI provider selected in Settings → AI |
| Wiktionary lookups | The word you look up | en.wiktionary.org |
| Update check (versions from GitHub only, once a day, can be turned off in Settings → About) | Nothing about you: only a request for the list of releases | api.github.com |
| Audio by link | The address you enter | That website |
| Web articles in the reader | The address you enter | That website |
| Downloads | Nothing about you — only the file request | github.com (offline dictionaries), cdn.jsdelivr.net and huggingface.co (speech-recognition and text-recognition models) |
| Reporting an AI answer | Your comment, the reported answer (if you choose to attach it), the AI provider and model name, the app version and platform | The Polymosta developers (a Google Form), or a pre-filled GitHub issue that you submit yourself |

These services process your requests under their own privacy policies. Polymosta does not send them any identifier of you or your device. If you want nothing to leave your device, use a local AI model (LM Studio or Ollama) and offline dictionaries.

## Android permissions

- **Internet** — for the features above.
- **Display over other apps** and **foreground service** — only for the optional background word strip (ADHD mode), started and stopped by you.
- **Microphone** — only for pronunciation and conversation practice. Speech is recognised on the device.
- **Notifications**, **run at startup** and **wake lock** — only for the optional daily reminder, which is off until you turn it on. It is scheduled on the device; nothing is sent anywhere.
- **Storage** (Android 9 and older only) — to keep your data folder in Documents.

## Children

Polymosta is not directed at children under 13 and does not knowingly collect any personal data from anyone.

## Changes and contact

Changes to this policy are published in this file, with the history visible on GitHub. Questions: open an issue at https://github.com/Vorchunello/polymosta-releases/issues.

---

# Polymosta — Политика конфиденциальности

*Обновлено 11 октября 2026.*

Polymosta — бесплатное приложение для изучения языков (Windows, Linux, Android). В нём нет аккаунтов, рекламы, аналитики и слежки. У разработчиков нет сервера, на который уходили бы твои данные.

**Остаётся на устройстве:** профиль, слова, заметки, книги, прогресс (md-файлы в папке на устройстве); настройки и API-ключи; запись с микрофона (распознаётся на устройстве и никуда не отправляется); фото и снимки экрана для распознавания текста; офлайн-словари.

**Уходит с устройства — только когда ты пользуешься функцией, которой это нужно:**

- **ИИ-функции** — текст запроса (слова и тексты, с которыми работаешь, языки, уровни, цель) уходит выбранному в настройках ИИ-провайдеру: по умолчанию OVHcloud AI Endpoints (серверы во Франции), либо любой другой из списка в настройках, либо локальная модель на твоём компьютере.
- **Перевод без ИИ** — слово или текст уходит выбранному переводчику: MyMemory (по умолчанию), Apertium, Google, Microsoft, DeepL, LibreTranslate, ModernMT, Яндекс, Baidu, NiuTrans, Youdao, Papago или Sarvam. С ключом действует политика самого сервиса.
- **Викисловарь** — искомое слово уходит на en.wiktionary.org; **статьи по ссылке** — адрес уходит на сайт статьи.
- **Проверка обновлений** (только версии с GitHub, раз в день, отключается в «Настройки → О программе») — запрос списка релизов на api.github.com, о тебе ничего не передаётся.
- **Загрузки** (словари, модели распознавания речи и текста) — с github.com, cdn.jsdelivr.net и huggingface.co; о тебе ничего не передаётся.
- **Жалоба на ответ ИИ** — комментарий, ответ (если приложишь), название провайдера и модели, версия приложения — разработчикам Polymosta (Google Форма) или в виде заполненного issue на GitHub, которое ты отправляешь сам.

Эти сервисы обрабатывают запросы по своим правилам; Polymosta не передаёт им идентификаторов тебя или устройства. Чтобы ничего не уходило с устройства, используй локальную модель (LM Studio, Ollama) и офлайн-словари.

**Разрешения Android:** интернет; показ поверх других приложений и фоновый сервис — только для полоски слов (режим СДВГ), которую ты сам включаешь и выключаешь; микрофон — только для тренировки произношения и разговора, речь распознаётся на устройстве; уведомления, запуск после включения телефона и пробуждение — только для напоминания, которое выключено, пока ты его не включишь, и планируется на самом устройстве; память — только на Android 9 и старше.

Приложение не предназначено для детей младше 13 лет. Вопросы — https://github.com/Vorchunello/polymosta-releases/issues.
