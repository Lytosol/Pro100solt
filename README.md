# Pro100solt
# Git + GitHub — Шпаргалка

---

## 📦 Первый пуш проекта на GitHub
cd путь/к/проекту
git init
git add .
git commit -m "Первый коммит"
git branch -M main
git remote add origin https://github.com/твой_ник/имя_репы.git
git push -u origin main

📤 Отправка изменений (push)
git add .
git commit -m "Что изменено"
git push
📥 Получить обновления с GitHub (pull)
git pull
Если истории отличаются (Git ругается):
git pull origin main --allow-unrelated-histories

🌿 Работа с ветками
▶️ Посмотреть ветки
git branch         # локальные
git branch -r      # удалённые

➕ Создать ветку
git checkout -b feature-name

🔄 Переключиться на ветку
git checkout main

🔗 Слить ветку в другую
git checkout main
git merge feature-name
git push

🗑 Удалить ветку
git branch -d feature-name               # локально
git push origin --delete feature-name   # на GitHub

🔧 Привязать ветку к origin/main (если не пушится)
git branch -u origin/main

🆘 Выйти из vim (если застрял в консоли)
:wq — сохранить и выйти
:q! — выйти без сохранения

💡 Полезности
🔐 Сохранить логин и токен навсегда
git config --global credential.helper store

✏️ Переименовать ветку
git branch -M старое_имя новое_имя
➕ Создать ветку
git checkout -b feature-name

🔄 Переключиться на ветку
git checkout main

🔗 Слить ветку в другую
git checkout main
git merge feature-name
git push

🗑 Удалить ветку
git branch -d feature-name               # локально
git push origin --delete feature-name   # на GitHub

🔧 Привязать ветку к origin/main (если не пушится)
git branch -u origin/main

🆘 Выйти из vim (если застрял в консоли)
:wq — сохранить и выйти
:q! — выйти без сохранения

💡 Полезности
🔐 Сохранить логин и токен навсегда
git config --global credential.helper store

✏️ Переименовать ветку
git branch -M старое_имя новое_имя➕ Создать ветку
git checkout -b feature-name

🔄 Переключиться на ветку
git checkout main

🔗 Слить ветку в другую
git checkout main
git merge feature-name
git push

🗑 Удалить ветку
git branch -d feature-name               # локально
git push origin --delete feature-name   # на GitHub

🔧 Привязать ветку к origin/main (если не пушится)
git branch -u origin/main

🆘 Выйти из vim (если застрял в консоли)
:wq — сохранить и выйти
:q! — выйти без сохранения

💡 Полезности
🔐 Сохранить логин и токен навсегда
git config --global credential.helper store

✏️ Переименовать ветку
git branch -M старое_имя новое_имя➕ Создать ветку
git checkout -b feature-name

🔄 Переключиться на ветку
git checkout main

🔗 Слить ветку в другую
git checkout main
git merge feature-name
git push

🗑 Удалить ветку
git branch -d feature-name               # локально
git push origin --delete feature-name   # на GitHub

🔧 Привязать ветку к origin/main (если не пушится)
git branch -u origin/main

🆘 Выйти из vim (если застрял в консоли)
:wq — сохранить и выйти
:q! — выйти без сохранения

💡 Полезности
🔐 Сохранить логин и токен навсегда
git config --global credential.helper store

✏️ Переименовать ветку
git branch -M старое_имя новое_имя