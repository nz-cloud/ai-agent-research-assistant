## 🧠🔍 AI Agent Research Wikipedia
Um agente de IA capaz de realizar pesquisas automatizadas na Wikipedia e na web, e salvar os resultados em um arquivo .txt

## 📌 Descrição
Este projeto é um assistente de pesquisa baseado em inteligência artificial que utiliza múltiplas ferramentas para obter e registrar informações:

🔎 WikipediaAPIWrapper: realiza buscas diretas na Wikipedia.

🌐 DuckDuckGo: realiza buscas gerais na web.

💾 Sistema de salvamento automático em arquivos .txt com o conteúdo encontrado.

Tudo isso é orquestrado por meio de um AI Agent usando o framework LangChain.

## 🚀 Tecnologias Utilizadas
Python

LangChain

OpenAI API (OPENAI_API_KEY)

Pydantic

## ⚙️ Como Executar
### Clone o repositório:
`git clone https://github.com/seuusuario/ai-agent-research-wikipedia.git`

### Crie e ative um ambiente virtual (opcional, mas recomendado):
`python -m venv venv`

`.\venv\Scripts\activate`


### Instale as dependências:
`pip install -r requirements.txt`


### Configure sua chave de API da OpenAI como variável de ambiente (.env):
OPENAI_API_KEY="sua-chave-aqui"

### Execute o projeto via terminal:
`python .\main.py`
