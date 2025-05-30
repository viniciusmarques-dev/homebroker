# Home broker

## Requerimentos

Cada projeto tem seus próprios requerimentos, mas uma ferramenta é comum a todos: o Docker.

### Docker

Dependendo do seu sistema operacional, você tem 2 opções para instalar o Docker:

- [Docker Desktop] - Interface gráfica para gerenciar e usar o Docker.
- [Docker Engine] - Apenas a engine do Docker, sem interface gráfica, chamado de Docker Nativo.

Se você tem 8GB ou menos de memória RAM, recomendamos o uso do Docker Engine, pois a interface gráfica do Docker Desktop + a execução dos containers pode consumir praticamente a memória da máquina, caso contrário usar o Docker Desktop é mais prático.

## Rodar a aplicação

Para rodar os projetos entre em cada pasta e siga as intruções.

Existe uma configuração para rodar todos os projetos em containers Docker.

Entre em cada **README.md** dos projetos para rodar os projetos. A ordem de execução é:

2. [Golang](./go/README.md)
1. [Nest.js](./nestjs-api/README.md)
3. [Next.js](./next-frontend/README.md)


## Arquitetura do projeto
![arquitetura](https://github.com/user-attachments/assets/e8bde689-8092-49e9-9f98-e98cc015c3d3)

## Diagrama de entidade e relacionamento
![diagrama](https://github.com/user-attachments/assets/3b234b0b-60d2-4b73-afb2-271211ec43d8)

## Diagrama de Websockets
![websocket](https://github.com/user-attachments/assets/a01a23b4-d5e8-4ecc-9553-c7a747d4904b)

## Websockets change-stream
![websocket-change-stream](https://github.com/user-attachments/assets/56657e19-04b8-4fce-94a6-753d9210d65d)
