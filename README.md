# Chatbot Interativo com Personas e Análise de Imagem

## 🚀 Visão Geral

Este projeto é uma aplicação de chatbot multifuncional que permite aos usuários interagir com diferentes personas de IA. A aplicação é construída em Python com a biblioteca Streamlit para la interface principal, mas também inclui componentes de uma interface web tradicional (HTML, CSS, JS).

O chatbot é capaz de manter um histórico de conversas, analisar imagens enviadas pelo usuário e adaptar seu estilo de resposta com base na "persona" selecionada.

## 📊 Dados Utilizados

**Nota Importante:** Quaisquer dados utilizados ou gerados por este chatbot (exemplos de personas, diálogos, imagens de exemplo, etc.) são **puramente fictícios** e foram criados apenas para fins de demonstração. Nenhuma informação representa pessoas ou cenários reais.

## ✨ Funcionalidades

- **Seleção de Personas:** O usuário pode escolher com qual tipo de assistente de IA deseja conversar (ex: especialista, criativo, etc.).
- **Interface Interativa:** Interface web principal criada com Streamlit para facilitar a interação, upload de arquivos e visualização do chat.
- **Processamento de Imagens:** Capacidade de receber uma imagem, analisá-la e discutir seu conteúdo.
- **Gerenciamento de Histórico:** O chatbot mantém o contexto da conversa para interações mais fluidas.
- **Componentes Web:** Inclui uma estrutura básica de frontend (`index.html`, `css`, `js`) que pode ser integrada ou servir como uma interface alternativa.

## ✔️ Tecnologias Utilizadas

- **Backend e IA:** Python, Streamlit, LangChain (ou bibliotecas de IA similares)
- **Frontend:** HTML5, CSS3, JavaScript
- **Gerenciamento de Chaves:** python-dotenv

---

## 🛠️ Como Executar o Projeto (Parte Streamlit)

### 1. Clone o Repositório

```bash
git clone [https://github.com/SEU-USUARIO/chatbot-personas-streamlit.git](https://github.com/SEU-USUARIO/chatbot-personas-streamlit.git)
cd chatbot-personas-streamlit
```

### 2. Crie e Ative o Ambiente Virtual

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Instale as Dependências

```bash
pip install -r requirements.txt
```

### 4. Configure as Chaves de API

- O projeto já inclui um arquivo `.env`. Certifique-se de preenchê-lo com suas chaves de API válidas.
  ```
  SUA_API_KEY="seu-valor-secreto-aqui"
  ```

### 5. Execute a Aplicação Streamlit

Para iniciar a interface principal do chatbot:

```bash
streamlit run app.py
```

A aplicação será aberta no seu navegador.

---
