# Папка решений
Т.к. работа с исходниками на **stepic.org** - это тьма и боль, будем хранить все исходники в гите (как батька завещал)

[Подробнее о использовании GitHub для stepic.org] (https://github.com/ilmen/tp-stepic/blob/master/solvers/how_use_github_with_stepic.pdf)

По умолчанию GitHub не принимает пустые папки, можно положить в крайние пустые папки файл .gitignore  
с содержимым:  
**# Ignore everything in this directory**  
**# Except this file**  
**!.gitignore**  

Судя из комментариев, при сдачи решения стоит удалить файл *default.conf* из папки */etc/nginx/sites-enabled*  
**sudo rm -rf /etc/nginx/sites-enabled/default**  
для того, чтобы избавиться от ошибки: ***Failed test #4. http://10.42.187.67/uploads/test.js didn't returned 200***  
После удаления создаем новый файл *default.conf*, содержащий текст:  
**server**  
**{**  
     **listen 80;**  
**}**
