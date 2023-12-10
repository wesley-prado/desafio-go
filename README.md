# Desafio Full Cycle Rocks!!

Este projeto é uma resposta a um desafio onde o objetivo era criar uma imagem Docker que imprime "Full Cycle Rocks!!" na linha de comando usango Go. A imagem Docker resultante tem um limite de tamanho de 2MB.

## Como usar

Para construir e executar a imagem Docker, você pode usar o seguinte comando:

```sh
docker-compose up --build
```

Este comando irá construir a imagem Docker usando o arquivo Dockerfile.prod no diretório go, e então executará o contêiner Docker. Quando o contêiner é executado, ele imprimirá "Full Cycle Rocks!!" na linha de comando.

## Baixar a imagem do Docker Hub

Você também pode baixar a imagem diretamente do Docker Hub usando o seguinte comando:

```sh
docker pull wesleypradodev/fullcycle:prod
```

Depois de baixar a imagem, você pode executá-la com o seguinte comando:

```sh
docker run wesleypradodev/fullcycle:prod
```

## Licença

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, veja o arquivo [LICENSE](https://github.com/wesley-prado/desafio-go/blob/main/LICENSE)
