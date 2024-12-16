# Imersão Fullcycle 20 - Sistema de rastreamento de veículos

![Imersão Full Stack && Full Cycle](https://events-fullcycle.s3.amazonaws.com/events-fullcycle/static/site/img/grupo_4417.png)

Participe gratuitamente: https://imersao.fullcycle.com.br/

## Requerimentos

Cada projeto tem seus próprios requerimentos, mas uma ferramenta é comum a todos: o Docker.

### Docker

Dependendo do seu sistema operacional, você tem 2 opções para instalar o Docker:

- [Docker Desktop] - Interface gráfica para gerenciar e usar o Docker.
- [Docker Engine] - Apenas a engine do Docker, sem interface gráfica, chamado de Docker Nativo.

Se você tem 8GB ou menos de memória RAM, recomendamos o uso do Docker Engine, pois a interface gráfica do Docker Desktop + a execução dos containers pode consumir praticamente a memória da máquina, caso contrário usar o Docker Desktop é mais prático.

Se você quiser saber mais detalhes sobre isto, veja nosso vídeo [https://www.youtube.com/watch?v=99dCerRKO6s](https://www.youtube.com/watch?v=99dCerRKO6s).

Se você estiver no Windows, use o WSL 2. Veja nosso tutorial [https://github.com/codeedu/wsl2-docker-quickstart](https://github.com/codeedu/wsl2-docker-quickstart).

## Rodar a aplicação

Rode todas as aplicações com o comando:

```bash
docker-compose up -d
```

Este comando irá subir todos os containers necessários para rodar todo o projeto

Acesse as pastas `golang-simulator`, `nestjs-api` e `next-frontend` e siga as instruções.

Como você já vai ter rodado todos os containers com o comando acima, mas instruções pule o passo de *levantar os containers*


## Arquitetura do projeto

![alt text](./arquitetura_projeto.png)
