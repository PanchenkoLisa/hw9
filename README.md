# hw9
При выполнении задания я использовала приложение Notepad++

### 1. Удалить все пустые строки.
Я использовала регулярное выражение \n\r и заменила на \0, таким образом, удалила все пустые строки.
![](https://github.com/PanchenkoLisa/hw9/blob/master/-qZCwlSoX54.jpg?raw=true)

К сожалению, остались пустые строки. Я решила, что в них есть пробелы и использовала регулярное выражение ^\s*$ и удалила пустые строки, в которых содержится только пробел.
![](https://github.com/PanchenkoLisa/hw9/blob/master/GCLb_4dXIgU.jpg?raw=true)

### 2. Найти всех князей и города, имя и название которых оканчивается на "слав".
Я использовала регулярное выражение [А-Я]+\w+слав+\w+ чтобы найти имена князей и города, содержащих в себе "слав" (не те, которые оканчиваются, так как в примере написаны слова в которых есть окончания, например, Ростиславу). 
У меня получилось 564 вхождения.
![](https://github.com/PanchenkoLisa/hw9/blob/master/M3xEIamk6P4.jpg?raw=true)

### 3. Найти все упоминания Новгорода. Учтите, что написание может быть разным.
Я использовала регулярное выражение (Новѣ?город[а-я]?|Новъ?город[а-я]?|Новгородц[а-я]?|Новагород[а-я]?|Новугород[а-я]?|Новгород[а-я]?) чтобы найти все упоминания Новгорода в летописи. 
У меня получилось 56 вхождений.
![](https://github.com/PanchenkoLisa/hw9/blob/master/BtS_HtR6e7U.jpg?raw=true)

### Бонусное задание
Бонусное задание я выполняла в несколько действий.
По очереди вставляя пробелы после необходимых знаков препинания.
![](https://github.com/PanchenkoLisa/hw9/blob/master/BUFQYhl6Ty4.jpg?raw=true)
![](https://github.com/PanchenkoLisa/hw9/blob/master/RZ6B58aXnxw.jpg?raw=true)
![](https://github.com/PanchenkoLisa/hw9/blob/master/rWtjeQGs8Wg.jpg?raw=true)
![](https://github.com/PanchenkoLisa/hw9/blob/master/mkqIC2mdLNQ.jpg?raw=true)
![](https://github.com/PanchenkoLisa/hw9/blob/master/FyAh7a6jSSo.jpg?raw=true)
![](https://github.com/PanchenkoLisa/hw9/blob/master/Ppy-SZVyFGc.jpg?raw=true)
![](https://github.com/PanchenkoLisa/hw9/blob/master/YXsIRoJ85DM.jpg?raw=true)

Итоговый файл я прикрепила в репозиторий.
