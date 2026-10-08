# 👨‍🍳 METRO France – Professional Culinary Glossary Dataset (French–English)

## Description

This dataset is a **bilingual French–English glossary of professional cooking terms** used in restaurants and commercial kitchens: knife cuts, cooking methods, sauces and stocks, pastry, bread baking, meat and fish preparation, molecular gastronomy, plating and kitchen utensils.

It is published by **METRO France**, the food and equipment wholesaler for professionals, for chefs, cooks, culinary students and everyone working in the restaurant industry.

It contains **152 terms** organized into **10 categories**, each with its French definition and English translation.

It is designed for:
- culinary training and learning French kitchen vocabulary,
- translation and localization of recipes and menus,
- recipe, menu and cooking content applications,
- AI assistants, chatbots and RAG systems,
- open data projects.

The dataset is available in **CSV** and **LLM-optimized JSON** formats.

---

## Key figures

- 152 culinary terms
- 10 categories
- 2 languages: French (original) and English (translation)

### Terms by category

- Advanced Pastry & Sweet Techniques (Pâtisserie Avancée & Techniques Sucrées): 18
- Plating, Presentation & Finishing (Dressage, Esthétique & Finitions): 18
- Professional Cuts & Knife Techniques (Découpes & Taillages Professionnels): 16
- Classic & Modern Cooking Methods (Modes de Cuisson Classiques & Modernes): 16
- Molecular Gastronomy & Culinary Science (Cuisine Moléculaire & Science Culinaire): 16
- Meat, Poultry, Charcuterie & Fish (Viandes, Volaille, Charcuterie & Poissons): 15
- Kitchen Utensils (Ustensiles de Cuisine): 15
- Sauces, Stocks, Thickeners & Liquid Preparations (Sauces, Fonds, Liaisons & Préparations Liquides): 14
- Dish Types & Preparations (Types de Plats & Préparations): 14
- Bread Baking, Viennoiserie & Sourdough (Boulangerie, Viennoiserie & Levains): 10

### Example terms

- Brunoise: 1–2 mm dice
- Julienne: thin sticks (5 cm × 1–2 mm)
- Déglacer (to deglaze): dissolve cooking juices
- Roux: butter + flour cooked together
- Sphérification (spherification): formation of gelled beads

---

## Dataset content

- `metro_culinary_glossary.csv`: classic tabular format (one row per term)
- `metro_culinary_glossary.json`: structured and hierarchical format (terms grouped by category)

### Main structure (CSV)

- `term_id`: unique identifier (METRO-GLOS-001…)
- `category_fr` / `category_en`
- `term_fr` / `term_en`
- `definition_fr` / `definition_en`
- `also_in_category_fr`: other category the term belongs to, if any
- `source`

### Main structure (JSON)

- `category_fr` / `category_en`
- `term_count`
- `terms`
  - term_id, term_fr, term_en, definition_fr, definition_en
- `source`

Some terms have several meanings depending on context (e.g. *Velouté* as a sauce or as a soup, *Poêle* as a cooking method or as a utensil). They appear once per category, with their own definition.

---

## Use cases

- Culinary schools, apprenticeships and kitchen staff training
- Translation of recipes, menus and technical sheets
- Cooking apps and recipe platforms
- AI-powered assistants and RAG pipelines for food service
- Open data and research projects

---

## Methodology

- Glossary compiled for METRO France for restaurant professionals
- Harmonized categories, duplicate removal and spelling corrections
- English translation of categories, terms and definitions; French terms that are standard in professional kitchens worldwide (brunoise, julienne, roux…) are kept as is
- Structured for **human and machine consumption**
- No personal data included

---

## License

CC-BY 4.0 – Attribution: METRO France (metro.fr)

---

## Disclaimer

Data represents a snapshot in time (October 2026) and may change.
No guarantee of completeness or permanent accuracy.

---

# 👨‍🍳 METRO France – Glossaire de la cuisine professionnelle (dataset français–anglais)

## Description

Ce dataset est un **glossaire bilingue français–anglais des termes de la cuisine professionnelle**, utilisés en restauration : découpes et taillages, modes de cuisson, sauces et fonds, pâtisserie, boulangerie, préparation des viandes et poissons, cuisine moléculaire, dressage et ustensiles de cuisine.

Il est publié par **METRO France**, grossiste alimentaire et matériel pour les professionnels, à destination des chefs, cuisiniers, élèves en formation et de tous les métiers de la restauration.

Il contient **152 termes** organisés en **10 catégories**, chacun avec sa définition en français et sa traduction en anglais.

Il est destiné à des usages de :
- formation culinaire et apprentissage du vocabulaire de la cuisine,
- traduction et localisation de recettes et de cartes,
- applications de recettes, de menus et de contenus culinaires,
- assistants IA, chatbots et systèmes RAG,
- projets open data.

Les données sont structurées et disponibles en **CSV** et **JSON optimisé pour les LLMs**.

---

## Chiffres clés

- 152 termes culinaires
- 10 catégories
- 2 langues : français (version originale) et anglais (traduction)

### Termes par catégorie

- Pâtisserie Avancée & Techniques Sucrées : 18
- Dressage, Esthétique & Finitions : 18
- Découpes & Taillages Professionnels : 16
- Modes de Cuisson Classiques & Modernes : 16
- Cuisine Moléculaire & Science Culinaire : 16
- Viandes, Volaille, Charcuterie & Poissons : 15
- Ustensiles de Cuisine : 15
- Sauces, Fonds, Liaisons & Préparations Liquides : 14
- Types de Plats & Préparations : 14
- Boulangerie, Viennoiserie & Levains : 10

### Exemples de termes

- Brunoise : dés de 1–2 mm
- Julienne : bâtonnets fins (5 cm × 1–2 mm)
- Déglacer : dissoudre les sucs de cuisson
- Roux : beurre + farine cuits
- Sphérification : formation de billes gélifiées

---

## Contenu du dataset

- `metro_culinary_glossary.csv` : format tabulaire classique (une ligne par terme)
- `metro_culinary_glossary.json` : format structuré et hiérarchique (termes regroupés par catégorie)

### Structure principale (CSV)

- `term_id` : identifiant unique (METRO-GLOS-001…)
- `category_fr` / `category_en` : catégorie
- `term_fr` / `term_en` : terme
- `definition_fr` / `definition_en` : définition
- `also_in_category_fr` : autre catégorie du terme, le cas échéant
- `source`

### Structure principale (JSON)

- `category_fr` / `category_en`
- `term_count`
- `terms`
  - term_id, term_fr, term_en, definition_fr, definition_en
- `source`

Certains termes ont plusieurs sens selon le contexte (ex. *Velouté* comme sauce ou comme soupe, *Poêle* comme mode de cuisson ou comme ustensile). Ils apparaissent une fois par catégorie, avec leur propre définition.

---

## Cas d'usage

- Écoles de cuisine, apprentissage et formation des équipes en cuisine
- Traduction de recettes, de cartes et de fiches techniques
- Applications culinaires et plateformes de recettes
- Alimentation de modèles IA (RAG, agents, assistants) pour la restauration
- Projets open data et recherche

---

## Méthodologie

- Glossaire compilé pour METRO France à destination des professionnels de la restauration
- Harmonisation des catégories, suppression des doublons et corrections orthographiques
- Traduction en anglais des catégories, termes et définitions ; les termes français utilisés tels quels dans les cuisines professionnelles du monde entier (brunoise, julienne, roux…) sont conservés
- Structuration orientée **machine + humain**
- Aucune donnée personnelle

---

## Licence

CC-BY 4.0 – Attribution : METRO France (metro.fr)

---

## Avertissement

Les informations peuvent évoluer dans le temps.
Ce dataset représente un état à date (octobre 2026), sans garantie d'exhaustivité ou d'exactitude permanente.

