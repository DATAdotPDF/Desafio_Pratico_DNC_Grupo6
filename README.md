
<p align="center">
  <img src="Visual/BECOMEX_BANNER.png" alt="Projeto SIDRA/IBGE - Banner Oficial">
</p>


# 📊 Análise de Dados Agrícolas do Brasil com SIDRA/IBGE

**Estudo exploratório com foco em lavouras brasileiras baseado na tabela 5457 da SIDRA/IBGE**

---

## 📋 Descrição do Projeto

Este projeto tem como objetivo organizar, tratar e explorar os dados públicos do IBGE sobre produção agrícola no Brasil, utilizando a **tabela 5457** do sistema SIDRA. 

A coleta é realizada manualmente via API, com foco nas variáveis relacionadas à produção, área plantada, área colhida, rendimento e valor de mercado das culturas.

---

## 📂 Estrutura do Projeto

```
📂 Estrutura do Projeto

📂 Estrutura do Projeto

Desafio_Pratico_DNC_Grupo6/
├── DATABASE/
│   └── SIDRA/
│       ├── RAW/
│       │   ├── (2022) SIDRA Top10 - 5457.xlsx
│       │   └── (2023) -  SIDRA Top10 - 5457.xlsx
│       └── TRATADOS/
│           ├── 2022/
│           │   └── (2022) Tratamento Específico por Métrica/
│           └── 2023/
│               └── (2023) Tratamento Específico por Métrica/
├── Metodologia/
│   ├── 📊 Apresentação do Projeto.pdf
│   └── Metodos/
│       ├── 01-Introdução-a-KDD-e-DM.pdf
│       └── crisp-dm.pdf
├── Python/
│   ├── Becomex_DNC_25(Grupo#6).ipynb
│   ├── Becomex_DNC_SIDRA_Limpo.ipynb
│   └── Tratamento_de_Dados_Agrícolas_–_SIDRA_5457_(Becomex_+_DNC)_GRUPO_6.ipynb
├── Visual/
│   ├── AUTO.png
│   ├── BECOMEX BANNER.png
│   ├── CAPA.png
│   ├── IMG BANNER.png
│   ├── LINKS.png
│   └── READ.png
├── .gitignore
└── README.md


```

---

## ⚙️ Instalação e Execução

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/Desafio_Pratico_DNC_Grupo6.git
cd Desafio_Pratico_DNC_Grupo6
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute os notebooks no Google Colab ou localmente.

---

## 🧪 Metodologia

O projeto segue uma abordagem exploratória baseada em:

- Leitura e tratamento de dados da tabela 5457
- Substituição de valores inconsistentes seguindo {NOTAS}
- Normalização e padronização de colunas numéricas
- Geração de relatórios e gráficos a partir dos DataFrames tratados

---

## 🌽 Variáveis Agrícolas Consideradas

Trabalhamos com **as 10 principais culturas exportadas pelo Brasil nos últimos 50 anos**, com base em engenharia de prompt e seleção prévia:

Soja, Café (em grão), Milho, Cana-de-açúcar, Algodão herbáceo, Arroz, Laranja, Fumo, Feijão, Trigo.

---

## 📈 Possibilidades de Análise

- Comparação por UF e município
- Evolução entre 2022 e 2023
- Rendimento e valor da produção por cultura
- Análise territorial (micro/mesorregião)

---

## 🔮 Trabalhos Futuros

- Integração com **Streamlit** para visualização interativa
- Uso de **ChromaDB** para consultas contextuais e embeddings
- Modelagem com **regressão linear** para prever produções
- Aplicação de **machine learning** para projeções futuras
- Automação do processo com **agentes de IA**

---

## 📚 Referências

- [SIDRA - Sistema IBGE de Recuperação Automática](https://sidra.ibge.gov.br)
- [sidrapy GitHub](https://github.com/arthur-vidal/sidrapy)
- [Alterações em Unidades de Medida - IBGE](https://sidra.ibge.gov.br/content/documentos/pam/AlteracoesUnidadesMedidaFrutas.pdf)
