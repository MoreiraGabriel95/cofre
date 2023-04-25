# Projeto Cofre

Esse é um projeto Java que implementa um cofre, onde é possível incluir, retirar, listar e fazer câmbio entre diferentes moedas, como Dólar, Euro e Real.

## Estrutura do Projeto

O projeto é composto pelos seguintes diretórios:

- `bin`: diretório onde são armazenados os arquivos compilados (.class)
- `src`: diretório onde estão os arquivos-fonte do projeto (.java)
- `.settings`: diretório com as configurações do projeto
- `.classpath`: arquivo de configuração do classpath do projeto
- `.project`: arquivo de configuração do projeto

## Como utilizar o Projeto

Para utilizar o projeto, é necessário ter o Java JDK instalado e configurado corretamente em seu ambiente de desenvolvimento.

Após fazer o download e extrair a pasta zipada, abra sua IDE de preferência e importe o projeto. Certifique-se de que a pasta raiz do projeto é a pasta em que você extraiu o arquivo zipado.

Após importar o projeto, execute o arquivo `Principal.java` presente na pasta `src` para iniciar o programa.

## Funcionalidades

O projeto implementa as seguintes funcionalidades:

- Incluir uma determinada quantia de dinheiro no cofre
- Retirar uma determinada quantia de dinheiro do cofre
- Listar o saldo do cofre em todas as moedas disponíveis
- Fazer câmbio entre as diferentes moedas disponíveis

## Classes do Projeto

O projeto é composto pelas seguintes classes:

- `Principal.java`: classe principal do projeto, responsável por executar o programa
- `Cofre.java`: classe responsável por armazenar as quantias de dinheiro no cofre e realizar as operações de inclusão e retirada
- `Moeda.java`: enumeração que define as moedas disponíveis no programa
- `Euro.java`
- `Dolar.java`
- `Real.java`
