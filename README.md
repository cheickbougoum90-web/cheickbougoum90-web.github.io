# Portfolio de Cheïck Abdoul Aziz BOUGOUM

**Data Engineer · Data Scientist · Data Analyst**

Site portfolio d'une page, hébergé gratuitement avec GitHub Pages : **[cheickbougoum90-web.github.io](https://cheickbougoum90-web.github.io/)**

Je suis élève ingénieur en dernière année à l'ESMT Dakar (spécialité Données et Intelligence Artificielle), basé à Dakar. Ce site présente mes projets, classés en trois profils, mes compétences techniques et un formulaire de contact.

## À propos de ce portfolio

Le site montre ma chaîne de valeur de la donnée, du stockage à la décision :
- **Stockage et ingénierie** : bases SQL et NoSQL, bases réparties, réplication, Big Data, virtualisation.
- **Science des données** : modèles de gradient boosting, vision par ordinateur, scoring, modèles de langage en local.
- **Analyse décisionnelle** : ETL, data warehouse, indicateurs et cartographie.

Chaque carte de projet renvoie vers un dépôt GitHub avec son README, ses scripts et son rapport, quand le dépôt est publié.

## 🚀 Projets

### Data Engineer

| Projet | Technologies | Dépôt |
| --- | --- | --- |
| API RESTful Airbnb NYC | Node.js, Express, Mongoose, MongoDB Atlas | [airbnb-api](https://github.com/cheickbougoum90-web/airbnb-api) |
| ReplicaSet MongoDB : haute disponibilité et failover | MongoDB, mongosh, services Windows | [mongodb-replicaset-haute-disponibilite](https://github.com/cheickbougoum90-web/mongodb-replicaset-haute-disponibilite) |
| Base de données répartie Oracle : fragmentation et Database Links | Oracle, SQL*Plus | [oracle-bdr-fragmentation-dblinks](https://github.com/cheickbougoum90-web/oracle-bdr-fragmentation-dblinks) |
| Traitement batch et streaming avec Apache Spark sur YARN (TP guidé) | Spark, Hadoop YARN, Docker, Java, Scala | [spark-batch-streaming-yarn-docker](https://github.com/cheickbougoum90-web/spark-batch-streaming-yarn-docker) |
| Infrastructure de virtualisation VMware ESXi 6.5 (projet d'équipe) | VMware ESXi, RAID 5, Dell PowerEdge | [esxi65-install-raid5-dell-r720](https://github.com/cheickbougoum90-web/esxi65-install-raid5-dell-r720) |
| Analyse Big Data de ventes | Hadoop, Hive, HiveQL, Python | Dépôt à venir |
| Bases NoSQL : MongoDB et Neo4j | MongoDB, Neo4j | Dépôt à venir |

### Data Scientist

| Projet | Technologies | Dépôt |
| --- | --- | --- |
| Scoring du risque de crédit (en cours) | Python, XGBoost, SHAP, FastAPI, Docker | [credit-risk-scoring](https://github.com/cheickbougoum90-web/credit-risk-scoring) |
| Détection de fraude Mobile Money (DataTour 2026) | Gradient boosting, PR AUC | Dépôt à venir |
| Détection de requins par vision par ordinateur (en cours) | YOLO, CVAT, Google Colab | Dépôt à venir |
| IA portable sur clé USB (en cours) | LLM local, OCR, outils déterministes | Dépôt à venir |

### Data Analyst

| Projet | Technologies | Dépôt |
| --- | --- | --- |
| Système d'Information Décisionnel Agricole | ETL, data warehouse | Dépôt à venir |
| SEN-HealthMap (ANSD Hackathon 2026) | Indice composite, cartographie géospatiale | Dépôt à venir |

## 🛠️ Compétences

- **Data Engineering** : SQL (Oracle), MongoDB, Neo4j, Hadoop (HDFS, YARN), Hive, Spark, ETL et data warehouse, Docker, AWS, VMware ESXi.
- **Data Science et IA** : Python, machine learning, gradient boosting (PR AUC), YOLO et CVAT, modèles de langage en local, systèmes experts.
- **Data Analysis et BI** : Power BI, Tableau, modélisation de données, Microsoft 365.

## 📁 Structure du dépôt

```
cheickbougoum90-web.github.io/
├── index.html                  Page unique du site
├── favicon-32x32.png           Icône de l'onglet
└── assets/
    ├── css/style.css           Styles (palette « Modern Tech »)
    ├── js/main.js              Scripts de la page
    ├── CV_BOUGOUM.pdf          CV téléchargeable depuis l'en-tête
    └── images/
        ├── image_profil.JPEG   Photo de profil
        └── projects_images/    Aperçus des cartes de projets
```

## 💻 Tester le site en local

```bash
git clone https://github.com/cheickbougoum90-web/cheickbougoum90-web.github.io.git
cd cheickbougoum90-web.github.io
python -m http.server 8000
```

Ouvrir ensuite `http://localhost:8000`. Après un `git push` sur la branche `main`, GitHub Pages met le site à jour en quelques minutes.

## ✏️ Ajouter un projet

1. Déposer l'image d'aperçu dans `assets/images/projects_images/`. GitHub Pages distingue les majuscules : `.JPG` et `.jpg` sont deux noms différents.
2. Copier une carte `project-card` dans la bonne catégorie de `index.html`, puis renseigner le titre, la description et le lien du dépôt.
3. Pour afficher un schéma ou une capture en entier, garder la classe `fit-contain` sur l'image.

## 📬 Contact

[LinkedIn](https://linkedin.com/in/che%C3%AFck-abdoul-aziz-bougoum-7264243aa) · [GitHub](https://github.com/cheickbougoum90-web) · cheickbougoum90@gmail.com

## Crédits

Le site est construit à partir d'un modèle de portfolio pour GitHub Pages, adapté et complété avec mes projets, mes textes et mes visuels.
