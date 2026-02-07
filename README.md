# 🧪 Projeto QA Júnior – Testes de API do IPMA

## 📌 Visão Geral
Este projeto faz parte do meu portfólio como QA Analyst Júnior e tem como objetivo demonstrar conhecimentos básicos em testes de API, utilizando a API pública do IPMA (Instituto Português do Mar e da Atmosfera).

O foco é validar se a API responde corretamente, retorna dados estruturados e lida adequadamente com cenários inválidos.

## 🎯 Objetivo
- Praticar testes de API com Postman
- Validar status codes e estrutura das respostas
- Executar testes funcionais simples e testes negativos
- Demonstrar organização e documentação de testes

## 🌍 API Utilizada
IPMA – Instituto Português do Mar e da Atmosfera  
Base URL: https://api.ipma.pt

## 🔗 Endpoints Testados
- Lista de Localidades  
  `GET /open-data/districts-islands.json`

- Previsão do tempo por cidade (Lisboa)  
  `GET /open-data/forecast/meteorology/cities/daily/1110600.json`

- Teste negativo – cidade inválida  
  `GET /open-data/forecast/meteorology/cities/daily/9999999.json`

## 🧪 Tipos de Testes
- Testes funcionais
- Validação básica de dados
- Testes negativos
- Testes automatizados simples no Postman

## ⚙️ Ferramentas
- Postman
- GitHub
- Markdown

## 📁 Estrutura do Projeto
