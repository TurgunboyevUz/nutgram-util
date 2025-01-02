# nutgram-util
Nutgram/Laravel helper

# Installation
1. Save file as app/Utils/Telegram.php
2. add Telegram.php path to composer.json to autoload section
```
{
    "autoload": {
        "psr-4": {
            "App\\": "app/",
            "Bot\\": "bot/",
            "Database\\Factories\\": "database/factories/",
            "Database\\Seeders\\": "database/seeders/"
        },
        "files": ["app/Utils/Telegram.php"]
    }
}
```

# Usage
If you are using VSCode and PHP Intelephense, it gives you suggestion while you type the method )

Aviable methods: sendMessage, forwardMessage, copyMessage, deleteMessage, editMessageText, editMessageReplyMarkup, answerCallbackQuery, isChatMember, isChatAdmin, inlineKeyboard, resizeKeyboard, removeKeyboard
