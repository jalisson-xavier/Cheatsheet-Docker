# Cheat Sheet - Docker

## Introdução
O Docker é uma plataforma que permite criar, distribuir e executar aplicações dentro de containers isolados e portáteis.

## Comandos Essenciais

## Gerenciar Imagens

| Bash									|Descrição				|
| --------------------------------------|-----------------------|
| 	`docker images` 						| # Listar 				|
| 	`docker build -t <nome_da_imagem> .`	| # Criar               |
| 	`docker rmi <nome_da_imagem>` 		| # Remover             |

## Gerenciar Containers

| Bash									|Descrição				|
| --------------------------------------|-----------------------|
| `docker ps` 							            | # Listar              |
| `docker ps -a`						          | # Listar ocultos      |
| `docker run -it <nome_da_imagem>`		| # Rodar               |
| `docker stop <nome_do_container>`		| # Parar               |
| `docker rm <nome_do_container>`		  | # Remover             |

## Outros Comandos Úteis

| Bash											| Descrição								|
|-----------------------------------------------|---------------------------------------|
| `docker volume create`, `docker volume rm`	| # Gerenciar volumes                	|
| `docker exec`									| # Executar comandos em um container	|
| `docker system prune`							| # Poda de recursos não utilizados  	|


## Conceitos Importantes

**Imagem** Um template a partir do qual os containers são criados.

**Container** Uma instância em execução de uma imagem.

**Dockerfile** Um arquivo de texto que contém todas as instruções para criar uma imagem.

**Volume** Uma forma de persistir dados fora do container.

## Dicas e Truques

Utilize **tags** para organizar suas imagens.

Explore as opções de cada comando para personalizar seu uso.

Utilize o Docker Compose para gerenciar aplicações com múltiplos containers.

## Referências

[Documentação oficial](https//docs.docker.com/)


