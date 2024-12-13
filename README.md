# Sonar config

## Instale o [Sonar-Scanner](https://docs.sonarsource.com/sonarqube-server/9.8/analyzing-source-code/scanners/sonarscanner/)

![Print da página do Sonar](/readme/pagina-sonar.png)

Configure o diretório bin no seu no PATH do sistema.

## Rode o container do servidor SonarQube

    docker-compose up -d

## Uso
Configure o arquivo de properties de acordo com o seu projeto.

#### Rode o Sonar

    sonar-scanner

#### Acesse o WebApp do [Sonar](http://localhost:9000).