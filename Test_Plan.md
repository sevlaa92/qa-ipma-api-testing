# 📋 Test Plan – IPMA API

## Objetivo
Definir a abordagem de testes para validar os principais endpoints da API pública do IPMA, garantindo que a API responde corretamente e retorna dados estruturados.

---

## Escopo
Estão incluídos neste plano:
- Testes do endpoint de lista de localidades
- Testes do endpoint de previsão do tempo por cidade
- Testes de cenários inválidos (teste negativo)

---

## Fora do Escopo
Não fazem parte deste projeto:
- Testes de performance
- Testes de carga
- Testes de segurança
- Testes de usabilidade

---

## Ambiente de Testes
- Postman
- API pública do IPMA
- Ambiente local

---

## Tipos de Testes
- Testes funcionais
- Validação básica da estrutura dos dados
- Testes negativos (entrada inválida)

---

## Critérios de Sucesso
- API responde com status code esperado
- Estrutura da resposta está correta
- Dados essenciais estão presentes
- API retorna erro apropriado para entradas inválidas
