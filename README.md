# Programação para Ciência de Dados — UFOP

Repositório com as atividades práticas e listas de exercícios da disciplina **Introdução à Ciência de Dados** da UFOP.

## Conteúdo

| Arquivo | Descrição |
|---|---|
| `Lista de exercícios em Python AULA 01.ipynb` | Exercícios introdutórios de Python |
| `Lista_de_exercícios_em_Python_AULA_02.ipynb` | Listas, tuplas, dicionários, sets, funções, lambda, arquivos |
| `aula_03_lista_exercicios_numpy_spotify.ipynb` | NumPy com dataset do Spotify (estatísticas, filtros, normalização, produto matricial) |
| `Aula_04_exercicios_spotify_pandas_gabarito.ipynb` | Pandas com dataset do Spotify |
| `Atividade_Pratica_Aula2.ipynb` | Atividade prática — análise exploratória com dataset Tips |

## Ambiente

O projeto usa um ambiente virtual Python (`.venv`). Para recriar:

```bash
python -m venv .venv
.venv\Scripts\activate
pip install pandas numpy matplotlib seaborn jupyter nbconvert kagglehub
```

## Observação sobre o dataset do Spotify

O notebook da Aula 03 usa `kagglehub` para carregar o dataset do Spotify. Em ambientes com restrição de rede (firewall corporativo), a célula de setup faz o download automático de uma fonte pública alternativa e armazena o arquivo localmente no cache do `kagglehub`, sem necessidade de configuração manual.

## Disciplina

- **Curso:** Ciência de Dados
- **Instituição:** UFOP — Universidade Federal de Ouro Preto
# ufop-introducao-a-programacao-ciencia-dados
