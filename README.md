ETL Process
Ce projet est une implémentation d'un processus ETL (Extract, Transform, Load) en Python. Il extrait des données à partir de fichiers CSV, JSON et d'une base de données SQL, applique des transformations aux données extraites, puis charge les données transformées dans une nouvelle table SQL.

Fonctionnalités : 

-Extraction de données à partir de fichiers CSV, JSON et d'une base de données SQL.

-Transformation des données extraites en supprimant la colonne "id" et en ajoutant une colonne "majeur".

-Chargement des données transformées dans une table SQL.

Prérequis :

Avant d'exécuter ce projet, assurez-vous d'avoir les éléments suivants :

-Python 3.10 installé sur votre système.
-Les bibliothèques Python suivantes installées : pandas, glob.
-Accès à une base de données SQL avec les autorisations nécessaires pour créer une nouvelle table.