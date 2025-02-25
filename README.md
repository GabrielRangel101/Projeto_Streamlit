# Spotify Songs Dashboard

Este projeto é um dashboard interativo desenvolvido com [Streamlit](https://streamlit.io/) para visualizar dados de músicas do Spotify.

## 📌 Funcionalidades
- Carregamento e cache de dados para melhor desempenho.
- Filtros para seleção de artistas e álbuns.
- Gráficos interativos para análise de streams e danceability.
- Layout responsivo com colunas para melhor organização das informações.

## 🚀 Como Executar o Projeto
### Pré-requisitos
- Python 3.7+
- Streamlit
- Pandas

### Instalação das Dependências

```sh
pip install -r requirements.txt
```

### Executando o Dashboard

```sh
streamlit run app.py
```

## 📂 Estrutura do Projeto
```
📁 Spotify-Dashboard
│── 01 Spotify.csv  # Arquivo de dados
│── app.py          # Código principal do dashboard
│── requirements.txt # Dependências do projeto
│── README.md       # Documentação do projeto
```

## 📜 Código Principal (`app.py`)
O código utiliza **Streamlit** para criar um painel interativo que permite:
- Selecionar um artista e visualizar seus álbuns.
- Exibir gráficos de **Streams** e **Danceability** por álbum.
- Utilizar `st.cache_data` para otimizar o carregamento do dataset.

## 🛠 Tecnologias Utilizadas
- **Python**
- **Streamlit**
- **Pandas**

## 📄 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para contribuir e melhorar!

---
Desenvolvido por Gabriel Rangel Lima 🚀

