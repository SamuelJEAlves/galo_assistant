# Galo Assistant

**Galo Assistant** é um assistente virtual baseado em **RAG (Geração Aumentada por Recuperação)** e **Modelos de Linguagem de Grande Escala (LLM)**, projetado para fornecer respostas precisas e contextualizadas sobre o **Clube Atlético Mineiro**, um dos clubes mais icônicos do futebol brasileiro.

## Funcionalidades Principais

- **Arquitetura baseada em RAG**: Combina busca de informações em bases de dados específicas com um modelo de linguagem para gerar respostas contextualizadas.
- **Análise exploratória de dados e visualização**: Inclui técnicas de processamento de linguagem natural e visualização gráfica para compreender e explicar o conjunto de documentos.
- **Processamento de texto avançado**: Usa bibliotecas como NLTK e PyMuPDF para extrair, tratar e limpar informações relevantes da base de conhecimento.
- **Incorporadores do Hugging Face**: Implementa modelo de embeddings, otimizado para português-br do Hugging Face, para vetorizar e captar conexões semânticas nos textos.
- **Pipeline otimizado**: Construído com LangChain e ChromaDB para oferecer desempenho e escalabilidade.

## Tecnologias Utilizadas

- **ChromaDB**: Banco de dados vetorial para gerenciar embeddings.
- **LangChain**: Orquestração de fluxos de trabalho baseados em LLM.
- **Hugging Face e Hugging Face Embeddings**: Modelos pré-treinados e embeddings para processamento de linguagem.
- **PyMuPDF**: Extração de conteúdo textual de documentos PDF.
- **NLTK**: Processamento de linguagem natural.
- **Ollama**: Ferramenta para gerenciamento e execução de LLMs localmente.
- **Análise de Dados e Data Viz (matplotlib e wordcloud)**: Ferramentas para explorar e visualizar a distribuição sintática.

## Como Usar

- Você deve ter o Ollama instalado na sua máquina com o modelo de linguagem disponível para uso.

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/galo_assistant.git
   cd galo_assistant

2. **Configure o ambiente virtual e instale as dependências**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # No Windows: venv\Scripts\activate
   pip install -r requirements.txt

3. **Execute o assistente**:
   ```bash
   python assistant.py

4. **Interaja com o assistente**: Faça perguntas sobre o Galão da Massa e explore interações dinâmicas!

## Exemplos de Uso

- "Quantos títulos o Atlético ganhou no Campeonato Brasileiro?"
- "Quando foi fundado o Galo?"
- "Quais são os maiores artilheiros da história do clube?"

## Divirta-se explorando o mundo do Clube Atlético Mineiro com o Galo Assistant! 🐓⚽
