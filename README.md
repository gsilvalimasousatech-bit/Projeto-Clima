# API de Clima com Flask, MySQL e Docker

## Autor
Gabriel Silva Lima de Sousa

## Descrição
Este projeto coleta dados de clima da API OpenWeather, armazena no MySQL e fornece rotas REST para consulta.

## Como executar
1. Instale Docker e Docker Compose.
2. Execute: `docker-compose up --build`
3. Acesse em: http://localhost:5000

## Rotas
- GET `/` - Testa API
- GET `/clima` - Retorna último registro
- POST `/coletar` - Coleta e salva novo registro

