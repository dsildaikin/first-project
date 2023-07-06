## __Шпаргалка. Базовые команды в консоли__

### Навигация

 - __pwd__ (от англ. print working directory, «показать рабочую папку») — покажи, в какой я папке;

 - __ls__ (от англ. list directory contents, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;

 - __ls -a__ — покажи также скрытые файлы и папки, названия которых начинаются с символа . ;

 - __cd first-project__ (от англ. change directory, «сменить директорию») — перейди в папку first-project;

 - __cd first-project/html__ — перейди в папку html, которая находится в папке first-project;

 - __cd ..__ — перейди на уровень выше, в родительскую папку;

 - __cd ~__ — перейди в домашнюю директорию (/Users/Username);

 - __cd /__ — перейди в корневую директорию.

 ```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git push"    --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
```
