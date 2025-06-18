# Baby-names-in-France-Visualisation

Membres de l'équipe:

- Membre 1: **Ouhiba Aymen**  
- Membre 2: **Garra Nohalia**  
- Membre 3: **Vu Julien**
- Membre 4: **Wande Wula Alfred**
- Membre 5: **Mbathe Mekontchou Paul**

# Analyse des Prénoms en France (1900–2020)
Ce projet propose une analyse exploratoire et interactive des prénoms donnés en France de 1900 à 2020, à partir des données ouvertes de l’INSEE. Il combine des visualisations temporelles, géographiques et genrées, le tout réalisé en Python via Pandas, Altair, GeoPandas et ipywidgets.

**Contenu du notebook**
Le notebook est structuré en plusieurs phases :


 **Phase 1 : Évolution temporelle**

Identification des prénoms les plus donnés (ex : Marie, Jean, Pierre...).

Visualisation de leur popularité au fil des décennies.

 **Phase 2 : Répartition géographique**

Cartographie des prénoms les plus attribués par département.

Mise en évidence des spécificités régionales.

 **Phase 2 bis : Focus départemental interactif**

Sélection d’un département via un menu déroulant.

Affichage dynamique du top 5 local des prénoms.

 **Phase 3 : Analyse par sexe**

Comparaison des prénoms les plus donnés aux filles et garçons.

Visualisations par barres et par courbes, avec distinction graphique du sexe.

 **Technologies utilisées**

Python 3.11

Pandas pour la manipulation des données

Altair pour les visualisations interactives

GeoPandas pour la carte des départements

Matplotlib / Seaborn pour les graphiques classiques

ipywidgets pour l’interactivité (menus déroulants)

**Données**

Source : INSEE - Fichiers des prénoms

Format : CSV (dpt2020.csv)

Données anonymisées et agrégées par sexe, prénom, année, et département.

# Comment exécuter ce projet
1. Cloner le dépôt
    
        git clone https://github.com/NohailaGarra02/Baby-names-in-France-Visualisation.git
        
        cd "Baby-names-in-France-Visualisation"
  
2. Créer un environnement virtuel

          python -m venv venv
          
          #Windows :
          .\venv\Scripts\activate
          
          #macOS/Linux :
          source venv/bin/activate
  
3. Installer les dépendances

          pip install -r requirements.txt
  
4. Lancer Jupyter Notebook

        jupyter notebook
   
__Ensuite, ouvre le fichier baby_names.ipynb pour explorer les visualisations interactives.__

# Prérequis

    Python 3.11 recommandé
    
    Les bibliothèques nécessaires sont listées dans le fichier requirements.txt (Altair, Pandas, GeoPandas, Matplotlib...).

