[< Содержание](./readme.md)

## git branch
---

**git branch *[параметры]*** - Просмотр, создание и удаление ветвления.

---
Список локальных веток. Текущая ветка отмечена *:

    git branch file.txt


Список всех веток (локальных и удаленных):

    git branch -a

Создать новую ветку на основе последнего коммита:

    git branch fix22

Переименовать ветку (не требует проверки):

    git branch -m fix2 realese3

Удалить локальную ветку:

    git branch -d {{branch_name}}
