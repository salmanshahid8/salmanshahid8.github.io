---
title: "EtudELEC Data, aggregated electricity consumption data from 400+ residential customers in France"
collection: publications
category: dataset
permalink: /publication/ds_2024_etudelec
date: 2024-09-09
venue: 'Recherche Data Gouv France'
paperurl: 'https://doi.org/10.57745/wiwmmk'
citation: 'Osonuga, S., Imard, V., <b>Shahid, M. S.</b>, Ferrari, J., Boisseau, C., Wurtz, F., Delinchant, B., Llerena, D., Roussillon, B., & Fadhuile, A. (2024). EtudELEC Data, aggregated electricity consumption data from 400+ residential customers in France [Dataset]. In <i>Recherche Data Gouv France</i>'
---

Data Card
=======
This is grouped and aggregated electricity consumption data from the EtudELEC study conducted by the Observatoire du Transition Energétique Grenoble (OTE-UGA).

If you find this dataset useful and like different groupings to be published or have any questions, please feel free to comment on the discussion dedicated to this dataset on the OTE forum .

The EtudELEC study only studies electricity consumption from residential dwellings around France. The study involved over 400 homes (individual houses and apartments) and spanned ~11 months from 25th October 2022 to 1st October 2023. The data is collected from the smart meter data (Linky data) which is only available with a time-step of 30 minutes. The data is in average watts consumed in a half-hour period.

For reasons for privacy in line with GDPR laws, personal data such as individual home consumption will be shared as aggregated datasets as opposed to individual data points. The data from the participants were aggregated based on the following groupings:
- Type of heating used and type of residence (stand-alone house vs apartment)

This dataset is best viewed in the "Tree" view below. A folder is created for each of the groupings and sub-folders exist for all the subsequent groups. Each group folder contains:
- a table of the minimum, mean, and maximum of the average power consumed for each 30-minute period (W), and
- a JSON file with aggregated demographics information (number of inhabitants in different age backets, socio-professional category, year of construction etc.) of the group

The datasets will be updated on a yearly basis following the renewal of consent of the panel members.