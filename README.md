# webpack-question
1) в папке src/js/ созданы test1.js и test2.js
2) test1 и test2 импортированы в src/index.js
3) после webpack сборки в консоль (dist/index.html) выводится ошибка "ReferenceError: test is not defined".
4) Ошибки не наблюдается если test1 и test2 подключаются последовательно <script src="..."></script> в dist/index.html.
5) Вопрос - почему происходит ошибка?
***
Спасибо.
