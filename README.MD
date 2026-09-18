# https://vasiliy-grishanin.github.io/workout-MAX/

# Workout Max

**Carnet de musculation pour iPhone, sans compte, sans abonnement, sans connexion.**

Workout Max est une application web qui s'installe sur l'écran d'accueil et fonctionne hors ligne. Elle sert à une seule chose : noter ses séries à la salle vite et bien, avec les valeurs de la dernière fois sous les yeux et un chrono de repos qui se lance tout seul.

- 622 exercices avec photos et consignes en français
- Préremplissage automatique depuis ton historique
- Chrono de repos fixe ou progressif, signal sonore et visuel
- Records détectés en direct, graphiques de progression
- Données stockées uniquement sur le téléphone
- Interface en 9 langues

---

## Sommaire

1. [Installation](#installation)
2. [Prise en main](#prise-en-main)
3. [Fonctionnalités](#fonctionnalités)
4. [Réglages](#réglages)
5. [Données et confidentialité](#données-et-confidentialité)
6. [Langues](#langues)
7. [Technique](#technique)
8. [Crédits](#crédits)

---

## Installation

Aucune boutique d'applications, aucun compte.

1. Ouvre la page de l'application dans **Safari** :
   `https://vasiliy-grishanin.github.io/workout-MAX/`
2. Appuie sur **Partager** puis **Sur l'écran d'accueil**.
3. Lance l'application depuis son icône. Elle s'ouvre en plein écran et reste disponible sans réseau après la première ouverture.

> Sur iPhone, l'installation doit se faire depuis Safari, pas depuis un autre navigateur.

## Prise en main

Au premier lancement, l'application demande la langue et l'unité (kg ou lb). Ensuite, trois façons de commencer :

| Depuis l'accueil | Ce qui se passe |
|---|---|
| **Démarrer** la séance proposée | Lance le prochain modèle de ta rotation |
| **Séance libre** | Séance vide, tu ajoutes les exercices au fur et à mesure |
| **Depuis un modèle** | Choisis un modèle (Push, Pull, Jambes…) |

Pendant la séance, chaque exercice affiche ses séries en lignes. La colonne **Précédent** montre ce que tu as fait la dernière fois, et les champs sont déjà remplis avec ces valeurs. Tu ajustes si besoin, tu coches, le chrono de repos démarre.

## Fonctionnalités

### Pendant la séance

- **Séries en lignes** : poids, répétitions, marge (répétitions en réserve) et coche de validation.
- **Préremplissage** : les valeurs viennent de la dernière séance normale où l'exercice a été fait. Pour un exercice jamais fait, ce sont les valeurs par défaut des réglages.
- **Propagation** : modifier une série met à jour les suivantes, sauf celles déjà validées ou éditées.
- **Types de série** : normale, échauffement, dégressive, jusqu'à l'échec. L'échauffement ne compte ni dans les records ni dans le volume.
- **Supersets** : lie deux exercices ou plus, le chrono ne se lance qu'après le dernier du groupe.
- **Records en direct** : poids max, max estimé sur une répétition, meilleure série, volume de séance. Une notification apparaît dès qu'un record tombe.
- **Notes** : une note persistante par exercice (réglage de machine, hauteur du siège) et une note libre par séance.
- **Remplacer** un exercice par un similaire (même muscle principal), **réorganiser** l'ordre, **retirer**.
- **Hors norme** : marque un exercice dont les valeurs ne doivent pas être reprises la prochaine fois (séance écourtée, machine différente). Les records comptent quand même.
- **Écran allumé** pendant toute la séance.
- **Reprise automatique** : la séance est sauvegardée à chaque action, elle survit à une fermeture de l'application.

### Chrono de repos

- Durée **fixe** ou **progressive** (temps de départ + ajout à chaque série), réglable par exercice et par défaut.
- Repos spécifique après une série d'échauffement.
- Boutons −15 s, +15 s et Passer. Signal sonore à 3, 2, 1 puis à zéro, avec flash de l'écran.
- Après zéro, le chrono continue en dépassement (affiché en orange) pour savoir combien de temps tu as réellement attendu.
- Chrono de **transition** après le dernier exercice, sans alarme.
- Les deux chronos s'arrêtent seuls au bout de 15 minutes.

### Suivi et statistiques

- **Fiche exercice** : photos de départ et d'arrivée, carte des muscles (face et dos), matériel, niveau, consignes d'exécution, records, courbe de progression (poids max, max estimé, volume) sur 1 mois, 3 mois, 1 an ou tout, historique complet.
- **Historique** des séances par mois, avec détail, comparaison à la séance précédente, partage en texte, modification ou suppression.
- **Stats** : calendrier des jours d'entraînement, semaines d'affilée, carte des muscles travaillés dans la semaine, tableau des séries par groupe musculaire et par semaine, courbe du poids de corps.
- **Résumé de fin de séance** : durée, séries, volume, records battus, comparaison avec la dernière fois.

### Organisation

- **Modèles** : listes d'exercices réutilisables (Push, Pull, Jambes…). Le modèle fixe la liste, les poids et répétitions viennent toujours de l'historique.
- **Rotation** : ordre des modèles ; l'accueil propose le suivant, sans jamais décider à ta place.
- **Mise à jour du modèle** proposée en fin de séance si les exercices ont changé.
- **Refaire** une ancienne séance en un appui, **séances favorites**, **exercices favoris** en tête de liste.
- **Exercices personnalisés** avec photo de la machine prise sur place.

### Catalogue d'exercices

- 622 exercices de musculation et de powerlifting, chacun avec deux photos.
- Noms et consignes en français, recherche en français ou en anglais.
- Filtres par groupe musculaire et par matériel.
- Modes de suivi par exercice : poids et répétitions, poids du corps, lesté, assisté, durée. Option unilatéral.

## Réglages

| Section | Options |
|---|---|
| Langue | 9 langues, voir plus bas |
| Séance | Unité kg ou lb, séries et répétitions par défaut, repos par défaut, colonne marge, propagation des valeurs, ajustement automatique de la marge, écran allumé |
| Signal de fin de repos | Par-dessus la musique, en baissant la musique, prioritaire, ou aucun son. Flash visuel. Bips à 3, 2, 1 |
| Apparence | Thème clair, sombre ou automatique |
| Sauvegarde | Export et import d'un fichier JSON, rappel si la dernière sauvegarde date de plus d'un mois |

> Sur iPhone en mode silencieux, seul le mode « Prioritaire » émet un son, et il peut interrompre la musique un instant. Le flash visuel fonctionne dans tous les cas.

## Données et confidentialité

- Tout est stocké **dans le navigateur du téléphone**. Aucun serveur, aucun compte, aucune télémétrie.
- Les photos personnelles sont stockées localement également.
- Pense à **exporter une sauvegarde** de temps en temps depuis les réglages : c'est le seul moyen de retrouver tes données si tu changes de téléphone ou si le stockage du navigateur est effacé.

## Langues

Interface disponible en français, russe, anglais, allemand, chinois, espagnol, hindi, italien et portugais.

Les noms et consignes des exercices existent en français et en anglais. Dans les autres langues, ils sont affichés en anglais.

## Technique

- Un seul fichier `index.html` autonome (HTML, CSS, JavaScript, données et photos incluses), environ 13 Mo.
- Aucune dépendance externe, aucun appel réseau à l'usage.
- `sw.js` met le fichier en cache pour le fonctionnement hors ligne, `manifest.webmanifest` et les icônes servent à l'installation sur l'écran d'accueil.
- Hébergé sur GitHub Pages.

Pour mettre à jour l'application, il suffit de remplacer `index.html` et `sw.js` dans le dépôt, puis de fermer et rouvrir l'application deux fois.

## Crédits

Photos et données d'origine des exercices : [free-exercise-db](https://github.com/yuhonas/free-exercise-db), domaine public (Unlicense). Traductions et consignes en français rédigées pour ce projet.
