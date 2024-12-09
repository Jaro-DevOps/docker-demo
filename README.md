Prosty projekt aplikacji Flask z dwoma endpointami, pokazujący konteneryzację za pomocą Dockera.

Instrukcja uruchomienia aplikacji Flask w kontenerze Docker : 

1. Najpierw sklonuj repozytorium na swój lokalny komputer:

    git clone https://github.com/Jaro-DevOps/docker-demo
    cd docker demo

2. Budowanie obrazu Docker :

    docker build -t docker-demo .

3. Uruchamianie aplikacji za pomocą Docker :

    docker run -d -p 5000:5000 docker-demo

4. Testowanie aplikacji:
Otwórz przeglądarkę i wejdź na adres:
http://localhost:5000/
http://localhost:5000/health 

5. Uruchamianie aplikacji za pomocą Docker Compose

    docker-compose up -d

Aplikacja będzie dostępna pod adresem:
http://localhost:5000/