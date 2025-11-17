# VidFlow

Projeto desenvolvido para aprender a buscar dados em uma API utilizando JavaScript.  
Durante este projeto, aprendi a fazer requisições assíncronas com `fetch`, tratar erros com `try/catch`, filtrar resultados com condicionais e percorrer as respostas da API usando `forEach`.

---

## 🚀 Objetivo do Projeto
O VidFlow foi criado com o propósito de praticar:
- Consumo de APIs REST  
- Manipulação de respostas assíncronas  
- Tratamento de erros  
- Filtragem de dados  
- Renderização dinâmica com JavaScript  

---

## 🧠 Conceitos Praticados

### 🔹 1. **Busca na API**
Utilizando `fetch()` para acessar um endpoint externo e aguardar o retorno com `async/await`.

### 🔹 2. **Tratamento de Erros (`try/catch`)**
Implementação de captura de falhas, como:
- API fora do ar  
- Endpoint inválido  
- Erros de rede  
- Respostas inesperadas  

Isso evita que a aplicação quebre e permite mensagens mais amigáveis ao usuário.

### 🔹 3. **Condicionais para Filtrar**
Usei `if`, `else if` e operadores lógicos para:
- Verificar se a API retornou dados válidos  
- Filtrar objetos específicos  
- Decidir o que exibir para o usuário  

### 🔹 4. **Uso do `forEach`**
Percorri os dados retornados pela API para montar dinamicamente:
- Cards  
- Listas  
- Resultados de busca  

## ▶️ Como Executar

1. Baixe ou clone o repositório:
```bash
git clone https://github.com/SEU-USUARIO/vidflow

2. Baixe e instale o JSON Server

3. Cole o comando no terminal:
json-server --watch .\backend\videos.json
