# unsecret
Download all docs and cases from http://unsecret.rusarchives.ru to csv file

Использование:
		unsecret [option]

Опции:
		--verbose         - Вывод большего количества информации на STDIN
		--fromfile <file> - Загрузка странички из файла (полезно для отладки регэкспов)
		--cases 		      - Загружать "дела"
		--docs 			      - Загружать "документы" (по умолчанию)
		--printpage 	    - Вывести скачанную страницу целиком
		--outfile <file>  - Название файла, в который выводится csv (по умолчанию - docs.csv и cases.csv)

Для обычного использования достаточно запуска: 

$./unsecret --docs
