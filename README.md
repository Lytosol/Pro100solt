# Pro100solt
# 🧠 Git + GitHub — Шпаргалка от Batir

Полезно для быстрой работы через консоль — минимум воды, максимум дела.

---

## 📦 Первый пуш проекта на GitHub

```bash
cd путь/к/проекту
git init
git add .
git commit -m "Первый коммит"
git branch -M main
git remote add origin https://github.com/твой_ник/имя_репы.git
git push -u origin main
📤 Отправка изменений (push)
bash
Копировать
Редактировать
git add .
git commit -m "Что изменено"
git push
📥 Получить обновления с GitHub (pull)
bash
Копировать
Редактировать
git pull
Если истории отличаются (Git ругается):

bash
Копировать
Редактировать
git pull origin main --allow-unrelated-histories
🌿 Работа с ветками
▶️ Посмотреть ветки
bash
Копировать
Редактировать
git branch         # локальные
git branch -r      # удалённые
➕ Создать ветку
bash
Копировать
Редактировать
git checkout -b feature-name
🔄 Переключиться на ветку
bash
Копировать
Редактировать
git checkout main
🔗 Слить ветку в другую
bash
Копировать
Редактировать
git checkout main
git merge feature-name
git push
🗑 Удалить ветку
bash
Копировать
Редактировать
git branch -d feature-name               # локально
git push origin --delete feature-name   # на GitHub
🔧 Привязать ветку к origin/main (если не пушится)
bash
Копировать
Редактировать
git branch -u origin/main
🆘 Выйти из vim (если застрял в консоли)
:wq — сохранить и выйти

:q! — выйти без сохранения

💡 Полезности
🔐 Сохранить логин и токен навсегда
bash
Копировать
Редактировать
git config --global credential.helper store
✏️ Переименовать ветку
bash
Копировать
Редактировать
git branch -M старое_имя новое_имя