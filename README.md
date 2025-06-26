1. Скачайте и разархивируйте проект
cd путь_до_разархивированной_папки/vk_tests
2. Запустить все тесты: mvn clean test
3. Чтобы запустить только класс SearchTests: mvn -Dtest=tests.SearchTests test

4.Получить отчет Allure2: mvn allure:serve
После этого откройте файл target/site/allure-maven/index.html в браузере.
