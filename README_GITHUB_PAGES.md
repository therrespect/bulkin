# Как разместить этот сайт на GitHub Pages

1. Создайте новый публичный репозиторий на GitHub (например `bulkin-site`).
2. Скопируйте содержимое папки `bulkin_site` в корень репозитория (или поместите в папку `docs/`).
3. Команды (локально):
```
git init
git add .
git commit -m "Initial Bulkin site"
git branch -M main
git remote add origin https://github.com/<ваш-имя-пользователя>/<bulkin-site>.git
git push -u origin main
```
4. В GitHub: зайдите в `Settings` → `Pages` → в разделе "Build and deployment" выберите `Deploy from a branch`, укажите `main` и папку `/ (root)` или `docs/` если вы положили туда файлы. Нажмите Save.
5. Через несколько минут сайт будет доступен по `https://<ваш-имя-пользователя>.github.io/<bulkin-site>/`.

Более подробная официальная инструкция: https://docs.github.com/en/pages/quickstart
