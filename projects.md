---
layout: page
title: Projects
permalink: /projects/  # Optionnel : définit l'URL de la page
---
[!Work in progress!]
## 🌐 Interactive Tool: OECD CRS Social Protection
A lightweight, open tool to turn OECD CRS data into reproducible evidence on Social Protection (SP) across donors, recipients, and countries.

- **📌 Description** : The OECD CRS offers granular data on Official Development Assistance (donors, recipients, amounts, purpose codes), but making it usable for SP analysis is challenging. This tool allows users to define SP flexibly, query the full CRS, download custom datasets (CSV/Parquet), and visualize trends, shares, and maps for any country or group.
- **📌 Prototype delivers** :
  - Interactive web map & charts: SP aid over time, country shares, donor/recipient rankings.
  - Custom SP definition: select CRS purpose categories or keywords; ready-made presets provided (“Core SP”, “Expanded SP”).
  - On-the-fly downloads and comparisons between countries or groups.
- **🌍 Programming languages and data used** : Python, DuckDB, React, CSV, Parquet, JavaScript.
- **🔗 GitHub Link** : [See project repository](#)  
- **🎯 Deliverables** : Public website with interactive maps/charts, user-defined SP classifications, downloadable datasets; global analysis article with 20-year ODA trends to SP.
- **👥 Beneficiaries** : Researchers, students, think tanks, policy teams — enabling transparent, reproducible, and shareable evidence on SP funding.


---
## 📊 Interractive Map : Social Student Aid 
An interactive tool that allows comparing the generosity of student aid systems across OECD countries.

- **📌 Description** : This interactive map visualizes student support and fee systems across some OECD countries using 2020 data from the SSFD, developed by the Swedish Institute for Social Research. The dataset is based on model family analyses to ensure comparability across countries and time. All values are adjusted for inflation and converted to USD using the 2020 PPP conversion rate from the IMF.
- **🌍 Programming languages and datas used** : JavaScript, HTML/CSS, GeoJSON, CSV.  
- **🔗 GitHub Link** : [See project](https://github.com/AlexisWck/europesocialstudentscheme.git)  
- **🗺️ Link to the interactive map** : [See map](https://alexiswck.github.io/europesocialstudentscheme/)
  <div style="flex: 1; text-align: center;">
    <img src="{{ site.baseurl }}/images/map.jpg" alt="Map illustration" style="max-width: 100%; height: auto;">
  </div>
