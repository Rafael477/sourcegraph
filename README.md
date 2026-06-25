# Sourcegraph Local

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow) ![Stack](https://img.shields.io/badge/stack-Docker%20Compose-blue)

## Descrição
Configuração local para executar uma instância do Sourcegraph via Docker Compose.

## Objetivo
Facilitar testes locais do Sourcegraph para busca, navegação e análise de código.

## Tecnologias utilizadas
- Docker
- Docker Compose
- Sourcegraph Server

## Funcionalidades
- Serviço `sourcegraph/server`.
- Volume persistente para dados locais.
- Configuração centralizada em `docker-compose.yaml`.

## Estrutura de pastas
```text
.
└── sourcegraph-local/
    └── docker-compose.yaml
```

## Como rodar o projeto
```bash
cd sourcegraph-local
docker compose up -d
```

Depois acesse a porta configurada no `docker-compose.yaml`.

## Variáveis de ambiente
Este projeto não utiliza variáveis de ambiente atualmente.

## Scripts disponíveis
Não há scripts npm neste projeto.

## Melhorias futuras
- Documentar portas exatas expostas pelo Compose.
- Adicionar comandos de parada e limpeza.
- Criar `.env.example` se forem adicionadas configurações customizadas.
- Validar versão da imagem Sourcegraph conforme necessidade do ambiente.

## Autor
Rafael Aniceto da Silva do Nascimento
