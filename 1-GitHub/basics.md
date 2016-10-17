# Основы GitHub #

#Настройка GitHub

1. Заполнить имя и email: 
	git config --global user.name "имя"
	git config --global user.email "ажрес электронки"
	git config --list // выведет все настройки

2. Получить справку 
	git help

3.	git init //подключаем папку к в git

4.	git status //получаем статус, что закомитето, а что нет

5.	git add . //добовляем все что есть в папке в git

6.	git commit -m "коментарий"

7.Заливаем на удаленный репозиторий
	…or create a new repository on the command line
	
	echo "# basics" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/StKovalev/basics.git
	git push -u origin master
	
	…or push an existing repository from the command line
	
	git remote add origin https://github.com/StKovalev/basics.git
	git push -u origin master	
 		