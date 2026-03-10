
[README_P8.md](https://github.com/user-attachments/files/25861192/README_P8.md)
# ⚙️ P8 — Pipeline ETL & Analyse Sociodémographique avec dbt + Snowflake

[![dbt](https://img.shields.io/badge/dbt-Cloud-FF694B?style=flat-square&logo=dbt&logoColor=white)](https://www.getdbt.com/)
[![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)](https://www.snowflake.com/)
[![SQL](https://img.shields.io/badge/SQL-Advanced-025E8C?style=flat-square&logo=sqlite&logoColor=white)](https://en.wikipedia.org/wiki/SQL)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org)

---

## 🎯 Objectif

En tant que Data Analyst junior chez **OpenClassrooms**, concevoir un pipeline de transformation complet pour analyser l'évolution du profil sociodémographique des étudiants Data sur 4 ans — de l'ingestion dans Snowflake jusqu'à la restitution des résultats.

---

## 🔍 Insight clé

> **La stack dbt + Snowflake, c'est le standard de l'industrie data aujourd'hui.**
> Ce projet simule un environnement professionnel réel : pipeline documenté et reproductible, conformité RGPD, enrichissement avec des données publiques INSEE, restitution à un public non technique.

---

## 🛠️ Compétences mobilisées

- Déploiement et configuration d'un projet **dbt Cloud**
- Déclaration des sources dans Snowflake via fichiers `.yml`
- Modélisation des transformations : staging → intermediate → mart
- **Tests de qualité des données** intégrés dans dbt
- Anonymisation et conformité **RGPD**
- Enrichissement avec données publiques **INSEE**
- Analyse sociodémographique : âge, genre, région sur 4 ans
- Restitution en 15 slides à un public non technique

---

## 💻 Outils utilisés

| Outil | Usage |
|---|---|
| dbt Cloud | Pipeline de transformation documenté et reproductible |
| Snowflake | Entrepôt de données cloud |
| SQL | Modèles de transformation |
| Python (Pandas) | Préparation des données externes INSEE |

---

## 📁 Contenu du dossier

```
P8/
├── models/
│   ├── staging/             # Modèles de nettoyage des sources
│   ├── intermediate/        # Transformations métier
│   └── mart/                # Tables finales pour analyse
├── sources.yml              # Déclaration des sources Snowflake
├── dataset_final.csv        # Jeu de données finalisé
└── presentation_P8.pdf      # Support de soutenance (15 slides)
```

---

## 💡 Ce que ce projet m'a appris

Un pipeline ETL ne vaut que s'il est **reproductible, documenté et testé**. dbt impose une discipline de travail qui transforme la transformation de données en véritable ingénierie logicielle — c'est exactement ce que les entreprises attendent d'un Data Analyst en 2026.
