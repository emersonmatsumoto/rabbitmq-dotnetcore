Executar rabbitmq no docker:
docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management-alpine

Gerar .exe para dotnet core:
dotnet build -r win10-x64