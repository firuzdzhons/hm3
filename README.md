# hm3
# Сборка (Build)
    docker build -t myapp:0.1 . 

# Запуск(Run)
    docker-compose -f .\docker.yaml up -d 

# Публикация в Docker Hub
    docker tag myapp:0.1 firuzdzhonsa/myapp:0.1 
    docker push firuzdzhonsa/myapp:0.1

# Команда для загрузки вашего образа
    docker push firuzdzhonsa/myapp