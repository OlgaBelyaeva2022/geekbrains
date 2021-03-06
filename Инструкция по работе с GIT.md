# Инструкция по работе с git. Руководство для начинающих. #

**git** — одна из самых популярных систем контроля версий, способ организации и поддержания версионности.

## Установка ##
Для установки git на Ваш компьютер Вам понадобится скачать его, пройдя по ссылке ниже:
установка Git для Windows, MAC, Linux: https://git-scm.com/downloads.

## Настройка ##
При первом использовании git необходимо представиться.

Для этого нужно ввести в терминале 2 команды:

git config --global user.name «Ваше имя английскими буквами» 

git
config --global user.email ваша почта@example.com


## Основные команды ##
* git init – инициализация локального репозитория;
* git status – получить информацию от git о его текущем состоянии;
* git add – добавить файл или файлы к следующему коммиту;
* git commit -m “message” – создание коммита;
* git log – вывод на экран истории всех коммитов с их хеш-кодами;
* git checkout – переход от одного коммита к другому;
* git checkout master – вернуться к актуальному состоянию и продолжить работу;
* git diff – увидеть разницу между текущим файлом и закоммиченным файлом;
* git branch - выводит список веток в репозитории;
* git branch new_branch_name - создаем новую ветку с именем new_branch_name;
* git branch -d new_branch_name - удаляем ветку с именем new_branch_name;
* git checkout new_branch_name - переходим на ветку new_branch_name;
* git log --graph - выводим список коммитов в виде красивого дерева;
* git merge new_branch_name - сливает ветку new_branch_name с текущей веткой.

*Дополнительная информация*: команда clear - очищает выдачу терминала; Initial comment - стандартный первый комментарий к новому документу.

## Команды для работы с удаленными репозиториями в git ##

* git clone адрес репозитория - команда позволяет склонировать внешний репозиторий на ПК;
* git pull - позволяет скачать все из текущего удаленного репозитория и автоматически сделать merge с нашей версией;
* git push - позволяет отправить нашу версию репозитория на внешний репозиторий (требует авторизации на внешнем репозитории).



## Github
Github - это сервис Microsoft, который позволяет интегрироваться с программой git и настроить удаленную работу с репозиторием.

**Как сделать pull request:**

1. сделать fork интересующего репозитория на Github;
2. сделать clone своей версиии репозитория с Github;
3. создать новую ветку и в нее вносить все изменения;
4. зафиксировать все изменения (сделать коммиты);
5. отправить свою версию в свой Github;
6. на сайте Github нажать кнопку compare & pull request.
