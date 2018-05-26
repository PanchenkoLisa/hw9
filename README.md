# hw9
При выполнении задания я использовала приложение Notepad++

### 1. Удалить все пустые строки.
Я использовала регулярное вырвжение \n\r и заменила на \0, таким образом, удалила все пустые строки.
![](https://github.com/PanchenkoLisa/hw9/blob/master/-qZCwlSoX54.jpg?raw=true)

К сожалению, остались пустые строки. Я решила, что в них есть пробелы и использовала регулярное выражение ^\s*$ и удалила пустые строки, в которых содержится только пробел.
![](https://github.com/PanchenkoLisa/hw9/blob/master/GCLb_4dXIgU.jpg?raw=true)

### 2. Найти всех князей и города, имя и название которых оканчивается на "слав".
Я использовала регулярное выражение [А-Я]+\w+слав+\w+ чтобы найти имена князей и города, содержащих в себе "слав" (не те, которые окансиваются, так как в примере написаны слова в которых есть окончания, например, Ростиславу). 
У меня получилось 564 вхождения.
![](https://github.com/PanchenkoLisa/hw9/blob/master/gpiHjLpqfq8.jpg?raw=true)

### 3. Найти все упоминания Новгорода. Учтите, что написание может быть разным.
Я использовала регулярное выражение Нов+\w+город+\w+ чтобы найти все упоминания Новгорода в летописи. 
У меня получилось 56 вхождений.
![](https://github.com/PanchenkoLisa/hw9/blob/master/3A4n1hP9RIo.jpg?raw=true)

Итоговый файл я прикрепила в репозиторий.
