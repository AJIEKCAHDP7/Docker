Установка Docker.


curl -fsSL https://get.docker.com -o get-docker.sh^C

sh get-docker.sh


// проверка установленной версии

docker compose version


// используется в Docker для отображения всех контейнеров, включая запущенные, остановленные, а также завершившиеся.

docker ps -a

// Удаление определенного контейнера по его имени.

docker rm container_name
