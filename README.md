
<p align="center">
  <img src="https://raw.githubusercontent.com/DATAdotPDF/Desafio_Pratico_DNC_Grupo6/main/00.%20Documentos/02.%20Visual/BECOMEX_BANNER.png" alt="SIDRA/IBGE Project - Official Banner">
</p>

# 📊 Brazilian Agricultural Data Analysis with SIDRA/IBGE

**Analytical dashboard based on SIDRA/IBGE Table 5457, with dimensional modeling and Power Query transformations**

---

## 📋 Project Description

This project was developed as part of DNC's Data Engineering course, sponsored by Becomex, using public data from SIDRA/IBGE Table 5457 (Municipal Agricultural Production). The goal is to build a reliable analytical solution based on 10 agricultural products with high economic relevance to Brazil.

All data modeling and transformation was performed in Power Query (Power BI), following a star schema architecture for clear exploratory analysis.

---

## 🗂️ Folder Structure

The project is organized in the group's Google Drive using a standard structure:

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

## 🧭 Methodology

- Selection of SIDRA Table 5457 with data from 2022 and 2023
- Definition of the 10 leading agricultural products by export value
- Creation of a dimensional model (star schema) with:
  - fato_agricultura
  - dim_ano
  - dim_produto
  - dim_variavel
  - dim_territorio
  - dim_nivel
- Data treatment and cleaning performed entirely in Power Query
- Visualization and exploration with Power BI

---

## 🌾 Selected Agricultural Products

1. Soybeans
2. Corn
3. Coffee beans
4. Sugarcane
5. Upland cotton
6. Oranges
7. Cocoa beans
8. Leaf tobacco
9. Beans
10. Sugar

---

## 📊 Visualizations and KPIs

The Power BI dashboard includes:

- General KPIs: production, area, and production value
- Filters by product, year, state, region, and geographic level
- Comparative analyses by region and crop
- Interactive map and time-series charts
- Modular structure with multiple pages

---

## 🔧 Tools Used

- Power BI and Power Query
- Google Drive for version control
- GitHub for documentation
- Python for the initial exploratory phase

---

## 🚀 Future Extensions

- Connect to APIs to automate the data source
- Predictive analysis with machine learning
- Add export data from MAPA and the Brazilian Federal Revenue Service
- Publish the dashboard in public environments

---

## 📚 References

- [SIDRA - IBGE](https://sidra.ibge.gov.br/tabela/5457)
- [Becomex - Tax Intelligence](https://becomex.com.br)
- [FAO Yearbook](https://www.fao.org/statistics/yearbook)
- [OECD/FAO Outlook 2023–2032](https://www.oecd-ilibrary.org/agriculture-and-food/oecd-fao-agricultural-outlook-2023-2032_088b15b4-en)
- [Project GitHub](https://github.com/DATAdotPDF/Desafio_Pratico_DNC_Grupo6)
- [Project Google Drive](https://drive.google.com/drive/folders/1w4MwEPiSkDE5ZhkNfDcaV3UusQ0-Jc--?usp=sharing)