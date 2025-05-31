# Pro100solt — Git + GitHub Шпаргалка

== Первый пуш ==
cd путь/к/проекту
git init
git add .
git commit -m "Первый коммит"
git branch -M main
git remote add origin https://github.com/твой_ник/имя_репы.git
git push -u origin main

== Отправить изменения ==
git add .
git commit -m "Комментарий"
git push

== Забрать изменения ==
git pull
# если ругается:
git pull origin main --allow-unrelated-histories

== Ветки ==
# посмотреть:
git branch           # локальные
git branch -r        # удалённые

# создать:
git checkout -b имя

# переключиться:
git checkout main

# слить в main:
git checkout main
git merge имя
git push

# удалить:
git branch -d имя                  # локально
git push origin --delete имя      # на GitHub

# привязать к origin/main:
git branch -u origin/main

== vim (если застрял) ==
:wq    сохранить и выйти
:q!    выйти без сохранения

== Полезное ==
git config --global credential.helper store     # сохранить логин/токен
git branch -M старое_имя новое_имя              # переименовать ветку
