[English](README.md)

<div align="center">

# Проверка подписок на каналы
Простой Telegram-бот, который работает только после подписки на все необходимые каналы  
Мой Телеграм-канал - [Клик](https://t.me/CreateTrigger)

<img src='https://github.com/user-attachments/assets/df9ecaa0-cd4b-40bd-b720-291d2f44c3e8' width=60%/>

</div>

## 📖 Описание

Для работы вам потребуется доступ к необходимым каналам и бот.

На какие группы необходимо подписаться можно прописать в коде, а можно доставать из базы данных.

## 🤖 Запуск бота

### 1. Для начала вам потребуeтcя клонировать репозиторий к себе на компьютер через Git Bash.

```git
git clone https://github.com/droptrigger/checking-a-channel-subscription-telegram.git
```

### 2. Установим все неободимые библиотки:

```pip
pip install aiogram
```

### 3. Переходим в https://t.me/BotFather и создаем бота. Разрешаем приглашать его в каналы (Должно написать`enabled`).
<div align="center">
<img src='https://github.com/user-attachments/assets/d82aff71-41dd-43c0-a41e-5344f8a6b404' width=60%/>
</div>

### 4. В том же BotFather копируем токен API.
<div align="center">
<img src="https://github.com/user-attachments/assets/16d2b471-2818-49c9-a248-4a8e77b37685" width=60% height=70%>
</div>

### 5. В [config](bot/data/config.py) вписываем этот токен вместо пропуска.

### 6. Добавляем бота в канал, копируем ссылку на этот канал.
<div align="center">
<img src="https://github.com/user-attachments/assets/05c61168-3e2e-42f3-b6b7-e139cb8b7e21">
</div>

### 7. Ссылку на канал всписываем в переменную __groups__ в [user_handlers](bot/handlers/user_handlers.py).
<div align="center">
<img src="https://github.com/user-attachments/assets/a1b40606-b288-46d0-90a9-2392c5c473c5">
</div>

## ✅ Well done! Теперь все должно работать.
