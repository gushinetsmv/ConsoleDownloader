ConsoleDownloader
=================

Консольная утилита для скачивания файлов по HTTP протоколу.
Для полной сборки jar-ки необходимо выполнить команду gradlew fatJar, чтобы все сторонние jar-ки, которые я использовал в коде, подтянулись бы в итоговую jar-ку.
Запускать из консоли можно так: java -jar ConsoleDownloader-all.jar -n 5 -l 200k -o output_path -f input_file
