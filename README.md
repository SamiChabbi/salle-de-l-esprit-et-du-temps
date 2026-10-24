# 🥋 Salle de l'Esprit et du Temps — NSI Terminale

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SamiChabbi/salle-de-l-esprit-et-du-temps/main)

Une salle d'entraînement pour trois chapitres de Terminale NSI : **la récursivité**, **diviser pour régner** et **la programmation orientée objet**.

**Version avec les corrections.** La version élève (sans les corrections) est ici : [salle-de-l-esprit-et-du-temps-eleve](https://github.com/SamiChabbi/salle-de-l-esprit-et-du-temps-eleve).

## Le principe

Pour chaque chapitre, on a rassemblé une **base d'exercices tombés pour de vrai** : épreuve écrite du bac (2021 à 2025), épreuve pratique du bac, et contrôles de Terminale publiés par des professeurs. Chaque question de la base a été rangée dans un **type** (ce qu'on demande vraiment). Le cours du chapitre est tiré de cette analyse : **ce qui tombe, et comment répondre à chaque type de question.**

Chaque chapitre a deux fichiers :
1. **Le cours** (`…_Cours.ipynb`), la méthode : les statistiques de la base, une méthode générale en 5 étapes, une fiche par type de question (comment la reconnaître, la méthode, un exemple, les pièges), et une fiche réflexe ;
2. **Les exercices** (`…_Exercices.ipynb`), du plus simple au plus difficile. **Les énoncés sont recopiés tels qu'ils sont tombés** (texte, code et figures d'origine), sans aide ajoutée. Dans cette version corrigée, chaque question porte une étiquette 🏷️ qui renvoie à sa fiche.

## Contenu

```
01_Recursivite_Cours.ipynb                la méthode · 8 types de questions (R1 à R8)
01_Recursivite_Exercices.ipynb            19 exercices · 77 questions
02_Diviser_pour_regner_Cours.ipynb        la méthode · 8 types de questions (D1 à D8)
02_Diviser_pour_regner_Exercices.ipynb    16 exercices · 73 questions
03_POO_Cours.ipynb                        la méthode · 8 types de questions (P1 à P8)
03_POO_Exercices.ipynb                    20 exercices · 90 questions
```

Dans cette version, chaque question a trois blocs séparés : 📝 **ÉNONCÉ**, ✅ **RÉSOLUTION**, 💡 **EXPLICATION PÉDAGOGIQUE**. Toutes les résolutions ont été exécutées : les 138 cellules de tests passent.

## Utilisation

- En ligne, sans rien installer : cliquer sur le badge **Binder** ci-dessus.
- Sur son ordinateur : ouvrir les notebooks avec Jupyter (ou VS Code), Python 3 standard, aucune bibliothèque à installer.

Exécuter les cellules **dans l'ordre** : certaines questions réutilisent les fonctions des précédentes.
