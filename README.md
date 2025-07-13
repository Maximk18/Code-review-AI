# Code-review-AI
Объяснение как пользоваться:
Бот ревьюит код из PR с помощью AI (OpenAI).
Установите зависимости: npm install node-telegram-bot-api @octokit/core openai.
TOKEN, GitHub токен, OPENAI_API_KEY.
Запустите: node bot7.js.
Команды: /start, /review owner/repo pr_number для ревью. Бот извлекает diff и отправляет в OpenAI.
