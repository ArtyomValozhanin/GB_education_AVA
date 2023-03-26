# Seminar #1 control of version

## 1 check-out install git
- Terminal (В установленном VSC открываем "терминал", проверяем что терпинал открыт и работает один для наших файлов)
- git version ore "git -v" (проверяем какая версия установлена в какой папке работаем)
## 2 git configuration
- git config (внесение данных пользователя name; E-mail)

(git config [< options >])

    --global (изменение "внешних" данных пользователя name; E-mail)
    --system (use system config file)
    --local (use repository config file)
    --worktree (use per-worktree config file)
    -f, --file < file > (use given config file)
    --blob <blob-id> (read config from given blob object)

- status (просмотр измененных и отслеживаемых файлов) 

## 3 repository initialization 
- git init (делает указанную папку "рабочей" для отслеживания изменяемых файлов)
## 4 save fail changes
- git add (добавдяет файл к отслеживанию изменений)
- git commit (добавляет коментарий, как правило к внесенному изменению)
- git commit -am (одновременно и сохраняет и коментирует файл)
## 5 added change to the repository
- git log (смотрим список сохранений)
## 6 getting info about the history of commits
- git log --oneline (показывает и сохранения и изменения)
## 7 comparison with the last commit
- git diff (показывает то, что было "закоммичено" ;))
## 8 Moves between saves
- checkout (переход на предыдущее сохранение **** как правило первые 4е символа заголовка сохранения)
- checkout master (возврат к последнему сохранению)
## 9 Brunch
- **git branch** (показывает ветку нахождения)
- **git branch new_branch** (создание < new_brubch > - текстовое название новой ветки) 
- **git checkuot** (переход по веткам с указанием заданного названия ветки)
- **git merge** (слияние веток, вводиться из ветик _master_ с указанием _наименования слияемой ветки_)
- **git branche -d** (удаление неиспользуемой ветки **-d** _(delete)_ с обязательным указанием наименования ветки)
- **git log --graph** (визуализирует ветвление git c указанием вносимых изменений)

## __.git ignore__ (файловая структура с вписанным в нее наименованием и расширением _всех_ ненужных для отслеживания файлов через **git**)
___________
# Terminal
- clean (очищает историю сообщений выше командной строки) 
