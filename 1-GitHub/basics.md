# ������ GitHub #

#��������� GitHub

1. ��������� ��� � email: 
	git config --global user.name "���"
	git config --global user.email "����� ����������"
	git config --list // ������� ��� ���������

2. �������� ������� 
	git help

3.	git init //���������� ����� � � git

4.	git status //�������� ������, ��� ����������, � ��� ���

5.	git add . //��������� ��� ��� ���� � ����� � git

6.	git commit -m "����������"

7.�������� �� ��������� �����������
	�or create a new repository on the command line
	
	echo "# basics" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/StKovalev/basics.git
	git push -u origin master
	
	�or push an existing repository from the command line
	
	git remote add origin https://github.com/StKovalev/basics.git
	git push -u origin master	
 		