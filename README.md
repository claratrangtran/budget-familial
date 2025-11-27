# budget-familial
Analyse complète des transactions bancaires : Extraction, nettoyage de données, et création d'un tableau de bord Power BI pour le suivi budgétaire.
🇫🇷 📊 Projet d'Analyse des Dépenses Familiales (2025)

🎯 Aperçu du Projet (FR)

Ce projet a pour but de fournir une vue complète et structurée des finances d'un ménage en transformant des données de transactions bancaires brutes en informations claires et exploitables via un tableau de bord interactif. Il s'agit d'un projet de bout en bout couvrant l'extraction de données, le nettoyage, la modélisation et la visualisation (Business Intelligence).

L'objectif principal est de catégoriser les dépenses et les revenus pour identifier les tendances de consommation, les coûts mensuels récurrents, et les opportunités d'optimisation budgétaire.

🛠️ Outils & Technologies (FR)

Source de Données : Fichiers CSV ou Excel extraits de comptes bancaires familiaux.

Nettoyage & Transformation : MS Excel / Power Query (Nettoyage, standardisation, enrichissement des données).

Modélisation & Requêtes : SQL (pour la structuration conceptuelle de la base de données et les requêtes complexes de catégorisation).

Visualisation (BI) : Power BI (Création du tableau de bord interactif).

🗂️ Étapes Techniques Clés (FR)

1. Extraction et Nettoyage de Données

Consolidation : Fusion des transactions de plusieurs comptes (membres de la famille) en un seul jeu de données.

Nettoyage : Traitement des valeurs manquantes, suppression des doublons, et standardisation des formats de date.

Enrichissement : Ajout de colonnes calculées pour les montants, la classification Débit/Crédit (Dépenses/Revenus).

2. Catégorisation et Modélisation (L'Analyse)

C'est l'étape la plus critique du projet.

Classification par Mots-Clés (SQL/Power Query) : Développement d'une logique basée sur les libellés de transaction pour assigner automatiquement une Catégorie Principale (ex: Logement, Transport, Alimentation) et une Sous-catégorie (ex: Essence, Courses, Prêt).

Modélisation : Création d'un modèle de données simple mais efficace dans Power BI, avec des tables de faits et des dimensions (Calendrier, Catégories).

Calculs DAX : Élaboration de mesures clés (KPIs) telles que : Dépenses Totales, Revenus Totaux, Dépenses Mensuelles, etc.

📈 Résultats et Insights (Le Tableau de Bord) (FR)

Le tableau de bord permet une exploration visuelle rapide des données.

Indicateur Clé

Résultat (Mois Type)

Insight Commercial/Personnel

Dépenses Totales

40,4K (ex: annuel)

Permet de visualiser l'ampleur des flux sortants sur l'année.

Revenus Totaux

33,3K (ex: annuel)

Permet de comparer immédiatement le solde net de la période.

Principales Catégories

Logement-Maison (33,44%), Achats & Services (19,63%)

Confirmation des postes de dépenses les plus lourds pour une cible d'économie.

Sous-Catégories

Frais d'entretien, Impôts, Alimentation

Identification précise des abonnements/frais fixes à réviser.

Visualisation Principale (FR)

Vision d'Ensemble : Cartes affichant les totaux pour une vue macro (Top Gauche).

Analyse Temporelle : Graphique à barres comparant les Dépenses et Revenus Mensuels (Centre Gauche) pour identifier les pics saisonniers.

Ventilation : Diagramme en secteurs des Catégories (Centre Droit) et un graphique à barres des Sous-catégories pour un focus détaillé.

Top 5 Des Établissements : Graphique "Où est-il?" pour identifier les principaux bénéficiaires des transactions.

🇬🇧 📊 Family Expense Analysis Project (2025)

🎯 Project Overview (EN)

This project aims to provide a complete and structured view of household finances by transforming raw bank transaction data into clear, actionable insights via an interactive dashboard. This is an end-to-end project covering data extraction, cleaning, modeling, and visualization (Business Intelligence).

The primary objective is to categorize expenses and revenues to identify consumption trends, recurring monthly costs, and opportunities for budget optimization.

🛠️ Tools & Technologies (EN)

Data Source : CSV or Excel files extracted from family bank accounts.

Cleaning & Transformation : MS Excel / Power Query (Cleaning, standardization, data enrichment).

Modeling & Queries : SQL (for conceptual database structuring and complex categorization queries).

Visualization (BI) : Power BI (Creation of the interactive dashboard).

🗂️ Key Technical Steps (EN)

1. Data Extraction and Cleaning

Consolidation : Merging transactions from multiple accounts (family members) into a single dataset.

Cleaning : Handling missing values, removing duplicates, and standardizing date formats.

Enrichment : Adding calculated columns for amounts, and classifying Debit/Credit (Expenses/Revenues).

2. Categorization and Modeling (The Analysis)

This is the most critical stage of the project.

Keyword Classification (SQL/Power Query) : Developing logic based on transaction labels to automatically assign a Main Category (e.g., Housing, Transportation, Food) and a Subcategory (e.g., Maintenance Fees, Groceries, Loan).

Modeling : Creating a simple but effective data model in Power BI, including fact tables and dimensions (Calendar, Categories).

DAX Calculations : Developing key measures (KPIs) such as: Total Expenses, Total Revenues, Monthly Expenses, etc.

📈 Results and Insights (The Dashboard) (EN)

The dashboard allows for quick visual data exploration.

Key Indicator

Result (Typical Month)

Commercial/Personal Insight

Total Expenses

40.4K (e.g., Annual)

Allows visualization of the scale of outflows over the year.

Total Revenues

33.3K (e.g., Annual)

Allows for immediate comparison of the net balance for the period.

Main Categories

Housing-Home (33.44%), Shopping & Services (19.63%)

Confirmation of the heaviest spending areas for targeted savings.

Subcategories

Maintenance Fees, Taxes, Food

Precise identification of subscriptions/fixed costs to review.

Main Visualization (EN)

Overall View : Cards displaying totals for a macro view (Top Left).

Temporal Analysis : Bar chart comparing Monthly Expenses and Revenues (Center Left) to identify seasonal peaks.

Breakdown : Donut chart of Categories (Center Right) and a bar chart of Subcategories for a detailed focus.

Top 5 Establishments : "Where is it?" chart to identify the main recipients of transactions.

🚀 Conclusion (EN)

This project illustrates my ability to manage the complete data analysis cycle, from initial cleaning to the creation of a decision-making tool (the Power BI dashboard). The focus on automated categorization demonstrates an essential skill in data structuring and quality.
