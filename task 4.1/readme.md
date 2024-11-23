# Инструкция по работе с GIT

![git-logo](./assets/Git-Logo-1788C.png)

---

## *Первоначальная настройка:*

- [git config --global user.name "[имя]"](./user.name.md)
- [git config --global user.email "[адрес электронной почты]"](./user.email.md)

---

## *Создание репозитория:*

- [git init [название проекта]](./init.md)
- [git clone [url-адрес]](./clone.md)

---

## *Операции с файлами:*

- [git rm [файл]](./rm.md)
- [git rm --cached [файл]](./rmc.md)
- [git mv [оригинальный файл] [новое имя]](./mv.md)

---

## *Игнорирование некоторых файлов:*

-  [.log build/ temp-](./lbt.md)
- [git ls-files --others --ignored --exclude-standard](./ign.md)

---

## *Сохранение фрагментов:*

- [git stash](./stash.md)
- [git stash pop](./stashpop.md)
- [git stash list](./stashlist.md)
- [git stash drop](./stashdrop.md)

---

## *Внесение изменений:*

- [git status](./status.md)
- [git diff](./diff.md)
- [git add [файл]](./add.md)
- [git diff --staged](./diffst.md)
- [git reset [файл]](./reset.md)
- [git commit -m "[сообщение с описанием]"](./commitm.md)

---

## *Коллективная работа:*

- [git branch](./branch.md)
- [git branch [имя ветки]](./branch.name.md)
- [git switch -c [имя ветки]](./switch.md)
- [git merge [имя ветки]](./merge.md)
- [git branch -d [имя ветки]](./branchd.md)

---

## *Просмотр истории:*

- [git log](./log.md)
- [git log --follow [файл]](./log.follow.md)
- [git diff [первая ветка]...[вторая ветка]](./diff2.md)
- [git show [коммит]](./show.md)

---

## *Откат коммитов:*

- [git reset [коммит]](./reset.commit.md)
- [git reset --hard [коммит]](./reset.hard.md)

---

## *Синхронизация с удалённым репозиторием:*

- [git fetch [удалённый репозиторий]](./fetch.md)
- [git merge [удалённый репозиторий]/[ветка]](./merge2.md)
- [git push [удалённый репозиторий] [ветка]](./push.md)
- [git pull](./pull.md)

---
## *References:*

GIT Logo by Jason Long - https://git-scm.com/downloads/logos, license [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)

LICENSE: [MIT](./license.md)