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

## 🧪 Tipos de Testes Realizados
- Testes funcionais  
- Validação básica de dados (estrutura e campos obrigatórios)  
- Testes negativos (entrada inválida)  
- Testes automatizados simples utilizando scripts no Postman  

---

## ⚙️ Ferramentas Utilizadas
- **Postman** – Execução das requisições e criação de testes automatizados simples  
- **GitHub** – Versionamento e organização do portfólio  
- **Markdown** – Documentação clara e estruturada do projeto  

---

## 📁 Estrutura do Projeto

qa-ipma-api-testing/
│
├── README.md
│
├── docs/
│ ├── Test_Plan.md
│ ├── Test_Cases.md
│ └── Bug_Report.md
│
└── postman/
└── IPMA_Postman_Collection.json


---

## 📊 Resultados Obtidos
- Validação de que a API responde corretamente aos endpoints testados
- Confirmação da estrutura esperada das respostas em JSON
- Verificação do comportamento da API em cenários inválidos
- Organização dos testes de forma clara e reutilizável

---

## 🚀 Próximos Passos
- Expandir testes para mais cidades
- Criar mais cenários negativos
- Executar a collection via Newman
- Evoluir a automação de testes

---

## ✅ Conclusão
Este projeto representa minha base prática em **testes de API como QA Analyst Júnior**, demonstrando capacidade de testar, analisar e documentar APIs de forma clara, simples e profissional.

---

📌 *Projeto desenvolvido para fins de estudo e portfólio.*

