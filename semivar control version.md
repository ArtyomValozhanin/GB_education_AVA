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
- add (добавдяет файл к отслеживанию изменений)
- commit (добавляет коментарий, как правило к внесенному изменению)
- am (одновременно и сохраняет и коментирует файд)
## 5 added change to the repository
- log (смотрим список сохранений)
## 6 getting info about the history of commits
- log --oneline (показывает и сохранения и изменения)
## 7 comparison with the last commit
- diff (что было "закоммичено" ;))
## 8 Moves between saves
- checkout (переход на предыдущее сохранение **** как правило первые 4е символа заголовка сохранения)
- checkout master (возврат к последнему сохранению)

# Terminal
- clean (очищает историю сообщений выше командной строки) 
