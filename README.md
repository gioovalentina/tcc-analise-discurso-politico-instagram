# TCC - Análise do Discurso Político no Instagram

Projeto de Trabalho de Conclusão de Curso (TCC) voltado à análise textual de publicações políticas no Instagram durante as campanhas eleitorais municipais brasileiras de 2024.

## Objetivo

Este trabalho busca analisar o discurso político de candidatos às prefeituras das capitais nordestinas brasileiras no Instagram, investigando:

- padrões linguísticos;
- termos mais frequentes;
- diferenças discursivas entre espectros ideológicos;
- relações entre discurso e resultado eleitoral;
- subgrupos relevantes presentes nos dados.

## Tecnologias Utilizadas
### Linguagem
- Python 3

### Bibliotecas
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- WordCloud

### Técnicas Aplicadas
- Limpeza textual
- Tokenização
- Remoção de stopwords
- Stemming
- Frequência de termos
- Word Clouds
- Descoberta de subgrupos (Subgroup Discovery)


## Estrutura do Projeto

```txt
tcc-analise-discurso-politico-instagram/
│
├── data/
│   ├── raw/
│   ├── preprocessed/
|   └── processed/
│
├── notebooks/
│   ├── preprocessing/
│   ├── analysis/
│   └── visualization/
│
├── results/
│   └── wordclouds/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Base de Dados
A base de dados contém os textos das publicações de candidatos às prefeituras das capitais nordestinas brasileiras durante o período eleitoral.

Os dados incluem:

- texto das postagens dos candidatos;
- alinhamento político;
- situação eleitoral (vencedor ou derrotado).

## Metodologia

O processo metodológico foi dividido nas seguintes etapas:

  1. Coleta de Dados
     
Coleta de publicações políticas no Instagram durante campanhas eleitorais.

  2. Pré-processamento Textual
     
Aplicação de técnicas de limpeza textual, incluindo:
  
  - remoção de caracteres especiais;
  - normalização textual;
  - tokenização;
  - remoção de stopwords;
  - stemming.

  3. Análise Exploratória
     
Análise estatística e textual dos dados:
  
  - frequência de palavras;
  - termos mais utilizados;
  - nuvens de palavras.
  
  4. Processamento de Linguagem Natural
     
Utilização de técnicas de PLN para representação e análise textual.

  5. Descoberta de Subgrupos

Aplicação de algoritmos de mineração de subgrupos para identificar padrões relevantes associados a:
  
  - alinhamento político;
  - vitória ou derrota eleitoral;
  - estratégias discursivas.

## Resultados Esperados
Espera-se identificar:

- diferenças discursivas entre candidatos;
- padrões ideológicos no vocabulário;
- associações entre discurso e sucesso eleitoral;
- grupos textuais relevantes por meio da mineração de subgrupos.

## Como Executar
Clone o repositório
```txt
git clone https://github.com/seu-usuario/tcc-analise-discurso.git
```

Acesse a pasta
```txt
cd tcc-analise-discurso
```

Instale as dependências
```txt
pip install -r requirements.txt
```

Execute os scripts
python scripts/executar_pipeline.py

Exemplos de Resultados
- Word Clouds
- As nuvens de palavras representam os termos mais frequentes utilizados pelos candidatos durante as campanhas eleitorais

Os subgrupos encontrados representam padrões discursivos relevantes associados às variáveis-alvo do estudo.

## Organização Científica
Este repositório foi estruturado para garantir:

- reprodutibilidade dos experimentos;
- organização dos dados;
- separação entre dados brutos e processados;
- documentação metodológica;
- transparência científica.

## Trabalhos Relacionados
O projeto fundamenta-se em pesquisas nas áreas de:

- Processamento de Linguagem Natural;
- Mineração de Textos;
- Ciência Política Computacional;
- Descoberta de Subgrupos;
- Análise de Discurso Político.

## Autor
Giovanna Valentina Esteves

Graduanda em Sistemas de Informação — Universidade de Pernambuco (UPE)

## Licença
Este projeto está licenciado sob a licença MIT.
