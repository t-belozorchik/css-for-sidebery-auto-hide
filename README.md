https://www.youtube.com/watch?v=bXH4hmZ8j3Q

# Сss-for-sidebery-auto-hide.
# Firefox Sidebar Auto-Hider / Автоскрыватель боковой панели Firefox

## English

I vibe-coded a simple auto-hider for the Firefox sidebar.  
To make it work, you need to take a few additional steps:

### Enable CSS Support

1. Open `about:config` in the address bar.
2. Find the `toolkit.legacyUserProfileCustomizations.stylesheets` preference and set it to `true`. This allows Firefox to use your `userChrome.css` file.

### Find Your Profile Folder

1. Open `about:support` in the address bar.
2. In the **Application Basics** section, locate the **Profile Folder** row and click the **Open Directory** button. This will open your current profile in your file manager.

### Create a Folder and Place the File

1. Inside your profile folder, create a new folder named `chrome` (if it doesn't already exist).
2. Move your `userChrome.css` file into this `chrome` folder.

### Restart Firefox

Restart Firefox for the changes to take effect.

---

## Русский

Навайбкодил простой автоскрыватель боковой панели в Firefox.  
Для работы необходимо выполнить несколько дополнительных действий:

### Включите поддержку CSS

1. Откройте `about:config` в адресной строке.
2. Найдите параметр `toolkit.legacyUserProfileCustomizations.stylesheets` и установите его в `true`. Это позволит Firefox использовать ваш файл `userChrome.css`.

### Найдите папку вашего профиля

1. Откройте `about:support` в адресной строке.
2. В разделе **Application Basics** (Основные сведения о приложении) найдите строку **Profile Folder** (Папка профиля) и нажмите кнопку **Open Directory** (Открыть папку). Это откроет ваш текущий профиль в файловом менеджере.

### Создайте папку и положите файл

1. Внутри папки вашего профиля создайте новую папку и назовите её `chrome` (если её ещё нет).
2. Переместите ваш файл `userChrome.css` в эту папку `chrome`.

### Перезапустите Firefox

Перезапустите Firefox, чтобы изменения вступили в силу.
