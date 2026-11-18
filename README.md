# NoteForce

![NoteForce: colored notes and checklists for Windows, macOS and Android](assets/billboard.png)

Colored notes and checklists for Windows, macOS and Android. One account on all your devices, edits show up in a fraction of a second. Free, no ads.

**Like NoteForce? [Support the project](https://app.lava.top/4179967925)** ([details](#support-the-project)) · [Русский ниже ↓](#русский)

## Download

| Platform | File |
|---|---|
| **Android** (almost every phone) | [NoteForce-arm64.apk](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce-arm64.apk) |
| Android, universal | [NoteForce.apk](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce.apk) |
| **Windows 10/11** (Intel/AMD) | [NoteForce-Windows.zip](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce-Windows.zip) |
| **Windows 11 on ARM** (Snapdragon: Surface Pro 11/12, Copilot+ PCs) | [NoteForce-Windows-arm64.zip](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce-Windows-arm64.zip) |
| **macOS 12 or later** (Apple Silicon and Intel) | [NoteForce-macOS.zip](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce-macOS.zip) |

The links always point to the latest version. All versions are in [Releases](https://github.com/U-Said/NoteForce-releases/releases).

## What the picture shows

1. **Colors.** 10 colors; notes can be filtered and sorted by color. With Pro, each of the 10 colors can get your own shade and name.
2. **Checklists.** Drag items to reorder; checked items move to the bottom. “Check all” and “Delete checked” are one tap away.
3. **Note password.** A locked note is encrypted on the device (AES-256-GCM); the server only receives ciphertext. Open it with the password, a fingerprint (Android), Touch ID (Mac) or Windows Hello.
4. **Instant sync.** An edit on one device appears on the other in about half a second. Offline everything works as usual, and changes are sent when you are back online.
5. **Tray and autostart (Windows and macOS).** NoteForce can start at login and live in the system tray or the Mac menu bar. Its menu creates a note or a checklist right away.
6. **Android widgets.** “Note” shows a chosen note on the home screen: tap a new widget to choose the note, the ⇄ button in the corner changes it. “Quick note” creates a text note or a checklist with one tap.

Also: archive, trash with restore, JSON backup, search across notes and inside a note, dark theme, grid or list view, English and Russian interface, and a detailed user guide in Settings.
Keyboard shortcuts on Windows (Ctrl) and Mac (⌘): N — new note, L — new checklist, F — search, S — save, Esc — close.

## NoteForce Pro

Everything above is free. Pro adds:

- **Color settings** — give any of the 10 colors your own shade (all notes of that color change on every device), a name (“Work”, “Home”, “Urgent”) that shows on cards, in the filter and in search, or remove colors you don’t use and add them back up to 10.
- **Spell check** — English and Russian at the same time; corrections with a right-click (Windows, Mac) or a tap (Android).
- **Reminders** — coming soon.

Pro is a one-time $5 purchase for your account: forever and on all its devices. Buying will open in one of the next updates.

## Getting started

1. Install NoteForce on each device (see below).
2. On the first device open the menu ☰ → **Account and sync** → **Sign up** and enter an email and a password.
3. On the other devices open the same screen, choose **Sign in** and enter the same email and password. Your notes appear by themselves.

Without an account NoteForce works too, but notes stay on that device only.

## Install and update

**Android.** Open the downloaded APK on the phone and allow installing from this source. If Google Play Protect warns about an unknown app, tap “More details” → “Install anyway”. A new version installs over the old one; notes are kept.

**Windows.** Unzip the archive to any folder and run `NoteForce.exe`. The app is not code-signed yet, so on first launch Windows may show “Windows protected your PC” — click “More info” → “Run anyway”. To update, quit the app (if it is in the tray: tray icon → “Exit”) and unzip the new version over the old one.

**Windows on ARM (Snapdragon).** Download `NoteForce-Windows-arm64.zip`. A “Bad Image” error with code `0xc0e90002` means Smart App Control blocks unsigned apps; NoteForce can only run after you turn it off in Windows Security → App & browser control.

**macOS.** Unzip `NoteForce-macOS.zip` and move **NoteForce** to the Applications folder. NoteForce for Mac is not signed by Apple yet, so the first launch is blocked: open **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to NoteForce (on macOS 14 and earlier you can also right-click the app → Open). To update, quit NoteForce (⌘Q) and replace the app with the new one.

## Where your notes are stored

Every device keeps a full copy, so your notes are available offline. For sync a copy is stored on a Supabase server in Frankfurt; each account sees only its own notes. Locked notes reach the server already encrypted — without your password nobody can read them.

## Support the project

NoteForce is free and has no ads. If it helps you, you can say thanks with a donation: **https://app.lava.top/4179967925** → “Send a donation”.

- Pick a preset amount ($5, $10, $50 or 50, 100, 500 ₽) or enter your own and leave a comment.
- Bank cards are accepted, including Russian ones (payment in rubles, SBP available), plus other methods the payment page offers.
- Payments go through lava.top. A donation is voluntary and non-refundable.

---

## Русский

Цветные заметки и чек-листы для Windows, macOS и Android. Один аккаунт на всех устройствах, правки видны через доли секунды. Бесплатно, без рекламы.

**Нравится NoteForce? [Поддержите проект донатом](https://app.lava.top/4179967925)** ([подробнее](#поддержать-проект))

### Скачать

| Платформа | Файл |
|---|---|
| **Android** (почти все телефоны) | [NoteForce-arm64.apk](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce-arm64.apk) |
| Android, универсальный | [NoteForce.apk](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce.apk) |
| **Windows 10/11** (Intel/AMD) | [NoteForce-Windows.zip](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce-Windows.zip) |
| **Windows 11 на ARM** (Snapdragon: Surface Pro 11/12, Copilot+ PC) | [NoteForce-Windows-arm64.zip](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce-Windows-arm64.zip) |
| **macOS 12 и новее** (Apple Silicon и Intel) | [NoteForce-macOS.zip](https://github.com/U-Said/NoteForce-releases/releases/latest/download/NoteForce-macOS.zip) |

Ссылки всегда ведут на последнюю версию. Все версии лежат в разделе [Releases](https://github.com/U-Said/NoteForce-releases/releases).

### Что умеет NoteForce

1. **Цвета.** 10 цветов, заметки можно отфильтровать и отсортировать по цвету. С Pro у каждого из 10 цветов может быть свой оттенок и название.
2. **Чек-листы.** Пункты перетаскиваются, отмеченные уходят вниз. Есть «отметить все» и «удалить отмеченные».
3. **Пароль на заметки.** Содержимое заблокированной заметки шифруется на устройстве (AES-256-GCM), на сервер уходит только шифротекст. Открыть можно паролем, отпечатком (Android), Touch ID (Mac) или Windows Hello.
4. **Мгновенная синхронизация.** Правка на одном устройстве появляется на другом примерно через полсекунды. Без интернета всё работает как обычно, а изменения уходят на сервер при подключении.
5. **Трей и автозапуск (Windows и macOS).** Программа может запускаться при входе в систему и жить в трее или строке меню Mac. Из её меню можно сразу создать заметку или чек-лист.
6. **Виджеты Android.** «Заметка» показывает выбранную заметку на рабочем столе: нажмите на новый виджет, чтобы выбрать её, а кнопкой ⇄ в углу смените. «Быстрая заметка» создаёт текст или чек-лист одним нажатием.

Ещё есть архив, корзина с восстановлением, резервная копия в файл JSON, поиск по всем заметкам и внутри заметки, тёмная тема, вид сеткой или списком, английский и русский интерфейс и подробная инструкция в Настройках.
Горячие клавиши в Windows (Ctrl) и на Mac (⌘): N — новая заметка, L — новый чек-лист, F — поиск, S — сохранить, Esc — закрыть.

### NoteForce Pro

Всё перечисленное выше бесплатно. Pro добавляет:

- **Настройки цветов** — любому из 10 цветов можно задать свой оттенок (все заметки этого цвета меняются на всех устройствах), название («Работа», «Дом», «Срочно»), которое видно на карточках, в фильтре и в поиске, или удалить ненужный цвет и снова добавлять цвета до 10.
- **Проверка орфографии** — русский и английский одновременно; варианты исправления по правой кнопке мыши (Windows, Mac) или нажатию (Android).
- **Напоминания** — скоро.

Pro — разовая покупка за $5 на аккаунт, навсегда и на всех его устройствах. Купить его можно будет в одном из ближайших обновлений.

### Как начать

1. Установите NoteForce на каждое устройство (инструкция ниже).
2. На первом устройстве откройте меню ☰ → **Аккаунт и синхронизация** → **Регистрация** и введите email и пароль.
3. На остальных устройствах откройте тот же экран, выберите **Вход** и введите те же данные. Заметки появятся сами.

Без аккаунта NoteForce тоже работает, но заметки хранятся только на этом устройстве.

### Установка и обновление

**Android.** Откройте скачанный APK на телефоне и разрешите установку из этого источника. Если Google Play Защита предупредит о неизвестном приложении, нажмите «Подробнее» и «Всё равно установить». Новая версия ставится поверх старой, заметки сохраняются.

**Windows.** Распакуйте архив в любую папку и запустите `NoteForce.exe`. Программа пока без цифровой подписи, поэтому при первом запуске Windows может показать окно «Windows защитила ваш компьютер». Нажмите «Подробнее» и «Выполнить в любом случае». Для обновления закройте программу (если она в трее, то значок → «Выход») и распакуйте новую версию поверх старой.

**Windows на ARM (Snapdragon).** Скачайте именно архив `NoteForce-Windows-arm64.zip`. Ошибка «Bad Image» с кодом `0xc0e90002` значит, что Интеллектуальное управление приложениями (Smart App Control) блокирует программы без цифровой подписи. Запустить NoteForce можно только после отключения этой функции: «Безопасность Windows» → «Управление приложениями и браузером».

**macOS.** Распакуйте `NoteForce-macOS.zip` и перенесите **NoteForce** в папку «Программы». NoteForce для Mac пока не подписан Apple, поэтому первый запуск заблокируется: откройте **«Системные настройки» → «Конфиденциальность и безопасность»**, пролистайте вниз и нажмите **«Всё равно открыть»** рядом с NoteForce (в macOS 14 и раньше можно также щёлкнуть программу правой кнопкой → «Открыть»). Для обновления завершите NoteForce (⌘Q) и замените программу новой.

### Где хранятся заметки

На каждом устройстве лежит полная копия, поэтому заметки доступны без интернета. Для синхронизации копия хранится на сервере Supabase во Франкфурте. Каждый аккаунт видит только свои заметки. Заблокированные заметки сервер получает уже зашифрованными: без вашего пароля их не прочитать.

### Поддержать проект

NoteForce бесплатный и без рекламы. Если программа вам пригодилась, можно сказать спасибо донатом: **https://app.lava.top/4179967925** → кнопка «Отправить донат».

- Можно выбрать готовую сумму ($5, $10, $50 или 50, 100, 500 ₽) или указать свою и оставить комментарий.
- Принимаются банковские карты, в том числе российские (оплата в рублях, есть СБП), и другие способы, которые предложит страница оплаты.
- Платёж проходит через платформу lava.top. Донат добровольный и не возвращается.
