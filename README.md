# Projeto de Processamento de Linguagem Natural (PLN) - Etapa 1

## Preparação para Análise de Sentimento com Tweets dos Presidenciáveis de 2023

### Objetivo:
O objetivo desta etapa do projeto é realizar a raspagem, carregamento e pré-processamento dos dados dos tweets dos presidenciáveis de 2023 para posterior análise de sentimento.

### Passos:
1. **Raspagem de Dados:** Utilização de ferramentas de web scraping para coletar os tweets dos presidenciáveis.
2. **Carregamento de Dados:** Carregar os dados coletados para um ambiente de análise, como um notebook Jupyter.
3. **Pré-processamento de Dados:** Limpar e preparar os dados para análise de sentimento, incluindo remoção de stopwords, tokenização, normalização de texto, entre outros.

### Tecnologias Utilizadas:
- Python
- Jupyter Notebook
- Bibliotecas de PLN, como NLTK, SpaCy, ou TextBlob
- Ferramentas de Web Scraping, como BeautifulSoup ou Scrapy

### Referências:
- Documentação oficial das bibliotecas utilizadas
- Tutoriais online sobre raspagem de dados e pré-processamento de texto

### Execução do Notebook:
1. Instale as bibliotecas necessárias:
    ```
    pip install nltk spacy beautifulsoup4
    pip install -qq transformers
    pip install unidecode
    pip install enelvo
    pip install wordcloud
    python -m spacy download pt_core_news_sm
    pip install --upgrade spacy
    ```
    
2. Execute o notebook Jupyter:
    ```
    jupyter notebook notebook_etapa1.ipynb
    ```
### Contribuição:
Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests com melhorias ou correções.

### Licença:
Este projeto é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.
