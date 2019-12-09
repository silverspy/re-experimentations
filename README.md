# Alfred - Majordome de Batman


## Modélisation

### Requirements Table

Voici la requirements table que nous avons récupéré :

![Alt text](/img.jpg?raw=true "Requirements table")

### Use Case Diagram (UC)

Nous avont modélisé le diagramme des cas d'utilisations du systéme. Pour l'instant nous avons détaillant en particulier le [cas d'utilisations](#requirements-table) "Afficher un indicateur santée de la maison"

![Alt text](/img.jpg?raw=true "UC")

### Diagramme de blocs (BDD)

Modélisations sous formes de Diagramme de blocs du systéme.

![Alt text](/img.jpg?raw=true "BDD")


### Diagramme de blocs internes (IBD)

Nous avons modélisés le bloc "Indicateurs santée" avec un [diagramme IBD](#use-case-diagram-uc)
.

![Alt text](/img.jpg?raw=true "IBD")

### Diagramme séquence

Diagramme séquence du [cas d'utilisations](#requirements-table) "Afficher un indicateur santée de la maison"

![Alt text](/img.jpg?raw=true "DS")

## Énoncé

## Modélisation

### Requirements Table

Voici la requirements table que nous avons récupéré :

![Alt text](/img.jpg?raw=true "Requirements table")

### Use Case Diagram (UC)

Nous avont modélisé le diagramme des cas d'utilisations du systéme. Pour l'instant nous avons détaillant en particulier le cas d'utilasion "Afficher un indicateur santée de la maison"

![Alt text](/img.jpg?raw=true "UC")

### Diagramme de blocs (BDD)

Modélisations sous formes de Diagramme de blocs du systéme.

![Alt text](/img.jpg?raw=true "BDD")


### Diagramme de blocs internes (IBD)

Nous avons modélisés le bloc "Indicateurs santée" avec un diagramme IBD.

![Alt text](/img.jpg?raw=true "IBD")

### Diagramme séquence

Diagramme séquence du cas d'utilisations "Afficher un indicateur santée de la maison"

![Alt text](/img.jpg?raw=true "DS")

## Énoncé

L’idée est de créer un système qui viendra rendre les services suivants :

- Affichage d’un indicateur de santé de la maison. Cet indicateur doit être capable de combiner les informations provenant de la mesure de plusieurs grandeurs physiques:
  - Température
  - Humidité
  - CO2
  - COV
  - Déplacement d’air (détecter un courant d’air)
  - Consommation électrique de la maison
  - Production électrique   
  - Quantité d’eau chaude restante 
  - Charge de la voiture électrique (optionnel en fonction de ce qu’affiche la voiture)
  - Ratio production / consommation
  - etc.
- Affichage des indicateurs détaillés sur différents domaines (en instantané et avec des graphiques) / en le ramenant à des indicateurs intelligibles pour l’humain 
  - Qualité de l’air 
  - Consommation électrique (par rapport à une journée type de la saison ou bien en €)
  - Production électrique (par rapport à une journée type de la saison ou bien en €)
  - Voiture (en capacité de déplacement)
  - Quantité d’eau chaude (en nombre de douche ou autres)
  - Ratio production/consommation électrique
- Affichage des prévisions pour la journée / pour la semaine
  - Qualité de l’air
  - Consommation électrique prévue
  - Production d’énergie prévue
  - La voiture sera chargée pour faire votre trajet quotidien à 16h30…
  - Vous pourrez prendre une douche chaude à 8h10 demain matin …
  - Prévision du ratio production / consommation
- Affichage de conseils / alertes pour bénéficier au mieux des capacités passives de la maison
  - Ouvrir la fenêtre pendant 10 minutes
  - Ne pas faire entrer de nouveaux visiteurs
  - Limiter à 5 pendant les 2 prochaines heures le nombre de personnes présentes dans la maison
  - N’oubliez pas de fermer la fenêtre
  - Faire des signaux sonores (~ alarme environnementale)
  - ….

Pour réaliser ce système vous devrez:
- éliciter les exigences (P1)
- Bien identifier le système et ses acteurs (P2)
- Définir les principales missions et scénarios d’utilisation du système (P2)
- Définir les principales fonctions du système, les intéractions et les échanges de flux entre elles (P2)
- Définir les principaux mode de fonctionnement du système (P2)

Organisation du travail : 
Le projet se déroulera en groupe de 2 étudiants

Livrables : 
- Une présentation de votre modèle sur la dernière heure, en expliquant chacun d’entre eux et les choix de conception que vous avez fait. 
- Le modèle (i.e., votre projet Eclipse) qui devra être envoyé par email avant le vendredi 8 décembre à minuit: benoit.combemale@irit.fr et jean-michel.bruel@irit.fr


Bon courage :)
Benoit and Jean-Michel
