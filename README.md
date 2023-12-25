# Закрепление знаний по Git для Яндекс.Практикума
## 1. Консольные команды 
* cd - команда, позволяет перемещаться по файловой системе. Указывается как _cd + %path%_
* ls - команда показывает файлы, находящиеся в данной директории
* pwd - команда показывает абсолютный путь к данной директории
* ~ - удивительный параметр для многих команд, обозначающий домашнюю директорию
* mkdir, touch - создание файлов или папок(директорий). mkdir - создание директории _mkdir + %name%_. touch - создание файла _touch + %name%_
* rm, rmdir - удаление папки или файла. rm - файла, rmdir - пустой директории. Если в директории есть какие-то файлы нужно использовать команду rm с флагом -r ( r - recursive)
* clip - копирование данных файла в буфер обмена. Имеет вид "clip < ~/directory/file.txt"
## 2. Git-команды
* git init - инициализация данной папки как репозитория
* git add - добавление изменений в коммит, используют комаду "git add .", чтобы добавить все изменения.
* git commit -m "message" - добавление в лог коммита с отчётом о изменениях. В ковычках обычно пишут изменения, которые произошли.
* git status - команда, позволяющая узнать, есть ли изменения в нашем репозитории
## 3. SSH-key
* ssh-keygen -t ed25519 "email" - генерация SSH ключа для связки удаленного репозитория и локального на компьютере.
* ssh -T git@github.com - команда, позволяющая связать аккаунт на GitHub и локального Git-a 
## 4. Connecting repositories 
* git remote origin %ssh-adress% - связывание двух репозиториев(удаленный и локальный)
* git push -u origin - загрузка всех коммитов и изменений на удаленный репозиторий
* git branch -M - обозначение названия ветки
