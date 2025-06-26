
<p align="center">
  <img src="https://raw.githubusercontent.com/DATAdotPDF/Desafio_Pratico_DNC_Grupo6/main/00.%20Documentos/Visual/BECOMEX_BANNER.png" alt="Projeto SIDRA/IBGE - Banner Oficial">
</p>






# 📊 Análise de Dados Agrícolas do Brasil com SIDRA/IBGE

**Dashboard analítico baseado na Tabela 5457 da SIDRA/IBGE, com modelagem dimensional e tratamento via Power Query**

---

## 📋 Descrição do Projeto

Este projeto foi desenvolvido no contexto do curso de Engenharia de Dados da DNC com patrocínio da Becomex, utilizando dados públicos da Tabela 5457 (Produção Agrícola Municipal) do sistema SIDRA/IBGE. O foco está na construção de uma solução analítica confiável, com base em 10 produtos agrícolas de alta relevância econômica para o Brasil.

Toda a modelagem e transformação de dados foi realizada no Power Query (Power BI), seguindo arquitetura em estrela (Star Schema), garantindo escalabilidade e clareza para análise exploratória.

---

## 🗂️ Estrutura de Pastas

O projeto está organizado no Google Drive do grupo conforme estrutura padronizada:

```
📦 /content/drive/MyDrive/DNC/Projetos/Becomex
├── 00. Documentos/
│   └── Visual/
├── 01. Base de dados/
│   └── 01. SIDRA/
│       ├── 00. Unused/
│       ├── 01. ELT/
│       └── Fato & Dimensao/
│           └── Refatoradas/
│               └── Star Schema/
│                   ├── Limpo/
│                   └── Tabelas_tratadas17 06/
├── 02. Empresa/
│   ├── 01. Metodologia/
│   └── 02. Visual/
├── 03. Python/
└── 04. Dash/
    ├── 01. Visual do tema Dash/
    ├── 02. DASHs/
    └── 03. PRINT DASHs/
```

---

## 🧭 Metodologia

- Seleção da Tabela 5457 da SIDRA com os dados de 2022 e 2023
- Definição dos 10 principais produtos agrícolas por valor de exportação
- Criação de modelo dimensional (Star Schema) com:
  - fato_agricultura
  - dim_ano
  - dim_produto
  - dim_variavel
  - dim_territorio
  - dim_nivel
- Tratamento e limpeza dos dados 100% no Power Query
- Visualização e exploração com Power BI

---

## 🌾 Produtos Agrícolas Selecionados

1. Soja em grão  
2. Milho em grão  
3. Café em grão  
4. Cana-de-açúcar  
5. Algodão herbáceo  
6. Laranja  
7. Cacau em amêndoa  
8. Fumo em folha  
9. Feijão em grão  
10. Açúcar

---

## 📊 Visualizações e KPIs

O dashboard Power BI apresenta:

- KPIs gerais: produção, área, valor da produção
- Filtros por produto, ano, UF, região e nível geográfico
- Análises comparativas por região e por cultura
- Mapa interativo e gráficos temporais
- Estrutura modular com múltiplas páginas

---

## 🔧 Ferramentas Utilizadas

- Power BI + Power Query  
- Google Drive para versionamento  
- GitHub para documentação  
- Python (apenas fase inicial exploratória)  

---

## 🚀 Expansões Futuras

- Conexão com APIs para automação da base
- Análises preditivas com machine learning
- Integração com dados de exportação (MAPA, Receita Federal)
- Publicação do dashboard em ambientes públicos

---

## 📚 Referências

- [SIDRA - IBGE](https://sidra.ibge.gov.br/tabela/5457)
- [Becomex - Inteligência Tributária](https://becomex.com.br)
- [FAO Yearbook](https://www.fao.org/statistics/yearbook)
- [OECD/FAO Outlook 2023–2032](https://www.oecd-ilibrary.org/agriculture-and-food/oecd-fao-agricultural-outlook-2023-2032_088b15b4-en)
- [GitHub do Projeto](https://github.com/DATAdotPDF/Desafio_Pratico_DNC_Grupo6)
- [Google Drive do Projeto](https://drive.google.com/drive/folders/1w4MwEPiSkDE5ZhkNfDcaV3UusQ0-Jc--?usp=sharing)
