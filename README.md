# LR6
# Лабораторная работа №6 "Система контроля версий"
## Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git API, опыт работы с локальным и удаленным репозиторием.
## Ход работы
### 1. Создание аккаунта на GitHub
[Скриншот регистрации](screenshots/1.jpg)
### 2. Fork репозитория
[Скриншот Fork](screenshots/2.jpg)
### 3. Установка Git
[Скриншот установки](screenshots/3.jpg)
### 4. Настройка Git
[Скриншот настройки](screenshots/4.jpg)
```bash
git config --global user.name "4315 Вострикова Виктория"
git config --global user.email "vika.vostrikova.02@mail.ru"
```
### 5. Клонирование репозитория
[Скриншот клонирования репозитория](screenshots/5.jpg)
```bash
git clone https://github.com/vstrv/LR6
```
### 6. Добавление файла через GitHub и подтягивание изменений
[Скриншот добавления файла](screenshots/6.jpg)
```bash
git pull origin master
```
### 7. Получение истории операций
[Скриншот истории операций](screenshots/7.jpg)
```bash
git log master
```
### 8. Просмотр последних изменений
[Скриншот последних изменений](screenshots/8.jpg)
```bash
git show
```
### 9. Слияние веток и разрешение конфликта
[Скриншот слияния веток](screenshots/9.jpg)
```bash
git merge ohh
```
### 10. Удаление ветки
[Скриншот удаления ветки](screenshots/10.jpg)
```bash
git branch -d ohh
```
### 11. Фиксация изменений
[Скриншот фиксации изменений](screenshots/11.jpg)
```bash
git add .
git commit -m "Описание изменений"
```
### 12. Откат коммита
[Скриншот отката](screenshots/12.jpg)
```bash
git reset --hard HEAD~1
```
### 13. Создание ветки для отчёта
[Скриншот создания ветки "отчет"](screenshots/13.jpg)
```bash
git checkout -b отчет
```

### 14. Оформление отчёта
Создание файла `README.md` и его заполнение.
[Скриншот создания и добавление папки screenshots](screenshots/14.jpg)
# Лог команд
```bash
git config --global user.name "4315 Вострикова Виктория"
git config --global user.email "vika.vostrikova.02@mail.ru"
cd c
cd..cd c
cd..cd C
cd /c/inf/lr
git clone https://github.com/vstrv/LR6
cd LR6
git pull origin master
git branch -a
git log master
git log HEAD
git show
git checkout -b ohh
git add .
git commit -m "была создана новая ветка"
git checkout master
git merge ohh
git branch -d ohh
echo "создали второй файл" > newfile2.txt
git add newfile2.txt
git commit -m "добавление второго файла"
git push origin
echo "##приветик^^" >> README.md
git add README.md
git commit -m "внесли изменения в существующий файл"
git push origin
echo "о нееет меня изменили локально" >> newfile.txt
git add newfile.txt
git commit -m "изменили первый созданный файл"
git push origin
git reset --hard HEAD~1
git status
git log --pretty=format:"%h %ad %an: %s"
git checkout -b отчет
git push -u origin отчет
mkdir screenshots
touch README.md
code README.md
echo "# Лабораторная работа №6" >> README.md
echo "## Цель работы" >> README.md~
echo "Изучение базовых возможностей системы управления версиями, опыт работы с Git API, опыт работы с локальным и удаленным репозиторием." >> README.md
echo "## Ход работы" >> README.md
echo "### 1. Создание аккаунта на GitHub" >> README.md
echo "\![Скриншот регистрации](screenshots/1.jpg)" >> README.md
git push origin отчет
git status
git add
git add .
git commit -m "заполнение отчета 1"
git push origin отчет
history
```

