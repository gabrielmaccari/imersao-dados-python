# Dashboard de Salários na Área de Dados

Este projeto é um dashboard interativo desenvolvido com [Streamlit](https://streamlit.io/) para análise de salários na área de dados, utilizando dados reais de profissionais do setor. O objetivo é permitir a exploração visual e detalhada dos salários, cargos, tipos de contrato, senioridade e distribuição geográfica dos profissionais de dados.

---

## Funcionalidades

- **Filtros Interativos:**  
  Permite filtrar os dados por ano, senioridade, tipo de contrato e tamanho da empresa diretamente na barra lateral.

- **Métricas Principais (KPIs):**  
  Exibe salário médio, salário máximo, total de registros e cargo mais frequente com base nos filtros aplicados.

- **Gráficos Dinâmicos:**  
  - **Top 10 cargos por salário médio:** Gráfico de barras horizontal.
  - **Distribuição de salários anuais:** Histograma.
  - **Proporção dos tipos de trabalho:** Gráfico de pizza (remoto, presencial, híbrido).
  - **Salário médio de Cientista de Dados por país:** Mapa coroplético interativo.

- **Tabela de Dados Detalhados:**  
  Visualização tabular dos dados filtrados para análise granular.

---

## Como executar

1. **Pré-requisitos:**
   - Python 3.8+
   - Instalar as dependências:
     ```
     pip install streamlit pandas plotly
     ```

2. **Execução:**
   - Salve o código em um arquivo chamado `app.py` na pasta `Alura`.
   - Execute o comando:
     ```
     streamlit run app.py
     ```
   - O dashboard abrirá automaticamente no navegador padrão.

---

## Estrutura do Projeto

```
aulas/
└── Alura/
    ├── app.py
    └── README.md
```

---

## Fonte dos Dados

Os dados utilizados são carregados diretamente de um arquivo CSV hospedado no GitHub:

```
https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv
```

---

## Principais Bibliotecas Utilizadas

- **Streamlit:** Interface web interativa.
- **Pandas:** Manipulação e filtragem dos dados.
- **Plotly Express:** Visualização gráfica avançada.

---

## Personalização

Você pode adaptar os filtros, gráficos e métricas conforme a necessidade do seu projeto ou dos dados disponíveis. Basta modificar o código no arquivo `app.py`.

---

## Exemplo de Uso

1. Selecione os filtros desejados na barra lateral (ano, senioridade, contrato, tamanho da empresa).
2. Analise os KPIs principais no topo do dashboard.
3. Explore os gráficos para identificar tendências e padrões salariais.
4. Consulte a tabela detalhada para inspeção dos dados filtrados.

---

## Licença

Este projeto é apenas para fins educacionais e de demonstração.

---

## Contato

Dúvidas ou sugestões?  
Abra uma issue ou entre em contato pelo GitHub!

---

**Divirta-se explorando os dados da área
