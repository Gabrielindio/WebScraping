### README.md  

# Web Scraper IMDb  

## Descrição  
Este projeto utiliza Selenium para extrair informações de filmes do site IMDb. O script acessa a página principal, navega pelo menu e coleta dados sobre os filmes, como posição no ranking, título, ano, duração, classificação, avaliação e quantidade de avaliações.  

## Tecnologias Utilizadas  
- Python  
- Selenium  
- WebDriver Manager  
- Pandas  
- Expressões Regulares (Regex)  

## Instalação  

1. Clone este repositório:  
   ```bash
   git clone https://github.com/Gabrielindio/WebScraping
   cd seu-repositorio
   ```

2. Instale as dependências:  
   ```bash
   pip install selenium webdriver-manager pandas
   ```

3. Certifique-se de ter o Google Chrome instalado.  

## Como Usar  

1. Execute o notebook Jupyter (`tratamento.ipynb`).  
2. O script abrirá o Chrome automaticamente e navegará pelo IMDb.  
3. Os dados serão extraídos e armazenados em um DataFrame Pandas.  

## Estrutura do Código  

- **Abertura do navegador** com Selenium  
- **Navegação pelo site IMDb**  
- **Extração dos dados** usando XPath e Regex  
- **Transformação e limpeza** dos dados com Pandas  
- **Exibição dos resultados**  

## Exemplo de Saída  

| Posição | Título | Ano | Duração | Classificação | Avaliação | Avaliação_total |  
|---------|--------|-----|---------|--------------|-----------|----------------|  
| 1 | Filme X | 2024 | 2h 30m | PG-13 | 8.5 | 1.5M |  

