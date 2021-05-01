# Vagrant

Criação de dois containers docker. Um usando a `imagem do MySQL` e outro com a `imagem do nginx` 
(servido na porta 80 da máquina host). A network criada usa o driver `bridge` o que permite a comunicação entre os dois containers.

## Pré Requisitos

Para rodar este projeto são necessárias as seguintes instalações: 

- [Docker](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Subindo os containers

Após instalação do Docker e do Docker Compose:

Clone o projeto em sua máquina:
```sh
git clone https://github.com/paclaraujo/docker-nginx-mysql
```

Inicie os containers usando:
```sh
sudo docker-compose up
```

Após o suceso do comando será possível acessar a página de boas vindas do nginx pelo `localhost:80`.

## Tecnologias usadas

- [Docker](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/compose-file/)

## Autora

* **Paloma Araujo** - [@paclaraujo](https://github.com/paclaraujo)