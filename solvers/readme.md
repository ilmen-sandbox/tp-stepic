# Папка решений
Т.к. работа с исходниками на **stepic.org** - это тьма и боль, будем хранить все исходники в гите (как батька завещал)

[Подробнее о использовании GitHub для stepic.org] (https://github.com/ilmen/tp-stepic/blob/master/solvers/how_use_github_with_stepic.pdf)

По умолчанию GitHub не принимает пустые папки, можно положить в крайние пустые папки файл .gitignore  
с содержимым:  
**# Ignore everything in this directory**  
**# Except this file**  
**!.gitignore**  

Судя из комментариев, при сдачи решения стоит удалить файл *default* из папки */etc/nginx/sites-enabled*.  
И создал новый, содержащий текст:
**server**  
**{**  
     **listen 80;**  
**}**
