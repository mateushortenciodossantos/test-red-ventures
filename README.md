# RV Test

Primeiro precisamos gerar a imagem docker localmente, rode docker build -t rv-test -f RV.Test/Dockerfile . 
a partir da raiz do projeto

Depois de gerada a imagem, aloque no m�nimo 4gb no Docker-Engine, pois usaremos o SQL Server on Linux e ele � bem pesado

rode docker-compose up -d

A aplica��o estar� dispon�vel em localhost:8080

Para acessar o Swagger � s� abrir localhost:8080/swagger

