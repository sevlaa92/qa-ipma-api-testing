# 🧪 Test Cases – IPMA API

## TC_API_001 – Lista de Localidades
**Descrição:** Validar se a API retorna a lista de localidades corretamente.  

- Endpoint: `GET /open-data/districts-islands.json`  
- Pré-condição: API disponível  

**Resultado Esperado:**  
- Status code 200  
- Resposta em formato JSON  
- Lista de localidades não vazia  

---

## TC_API_002 – Previsão do Tempo por Cidade (Lisboa)
**Descrição:** Validar se a API retorna a previsão meteorológica para uma cidade válida.  

- Endpoint: `GET /open-data/forecast/meteorology/cities/daily/1110600.json`  
- Pré-condição: City ID válido  

**Resultado Esperado:**  
- Status code 200  
- Campo `forecastData` presente  
- Dados de previsão disponíveis  

---

## TC_API_003 – Cidade Inválida
**Descrição:** Validar o comportamento da API ao receber um identificador de cidade inválido.  

- Endpoint: `GET /open-data/forecast/meteorology/cities/daily/9999999.json`  
- Pré-condição: City ID inexistente  

**Resultado Esperado:**  
- Status code 400 ou 404  
- API retorna erro apropriado  
