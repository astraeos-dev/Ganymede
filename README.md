<p align="center"><img src="assets/brand/icon.svg" width="128" height="128" alt="Ganymede"></p>

# Ganymede — calculatrice scientifique pour Android

> Application Android de calcul scientifique : calculatrice, convertisseur, traceur de fonctions et plus de cent outils
> (électronique, maths, physique, chimie, santé) et fiches de référence.

[![Licence MIT](https://img.shields.io/github/license/astraeos-dev/Ganymede?label=licence)](LICENSE)
![Android](https://img.shields.io/badge/Android-6.0%2B-3ddc84?logo=android)
![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7f52ff?logo=kotlin)

<a href="https://buymeacoffee.com/gregorychau"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" height="40"></a>

**Essayer** : la plupart des outils sont aussi dans la [version web](https://astraeos-dev.github.io/personnal-site/#/ganymede),
sans installation. Une idée, un problème ? [Ouvrir une demande](https://github.com/astraeos-dev/Ganymede/issues/new/choose).

**Projet actif** · un des projets d'Astraeos : [site web](https://astraeos-dev.github.io/personnal-site/#/ganymede) ·
[Céleste](https://github.com/astraeos-dev/Celeste_App) · [Céleste pour Home Assistant](https://github.com/astraeos-dev/Celeste_HA)

---

## Présentation

Ganymede regroupe dans une seule application les calculs du quotidien des techniciens, étudiants et curieux. La plupart
des calculateurs existent aussi dans la [version web](https://astraeos-dev.github.io/personnal-site/#/ganymede), utilisable sans
installation depuis un navigateur.

## Fonctionnalités

- **Calculatrice** scientifique avec historique
- **Convertisseur d'unités**
- **Traceur de fonctions** : courbes interactives en 2D
- **Électronique** : loi d'Ohm et puissance, codes des résistances (anneaux et CMS) et des condensateurs, valeurs
  normalisées, associations série/parallèle, pont diviseur, résistance de LED, temporisateur 555, filtres passifs,
  réactance, impédance et résonance RLC, constante de temps, ampli-op, polarisation de transistor, diode Zener,
  transformateur, pont de Wheatstone, triangle-étoile, chute de tension et section de câble, bobines, batteries, coût
  de l'énergie
- **Mathématiques** : second degré, matrices, pourcentages, PGCD/PPCM, dérivées et intégrales, transformées de Laplace,
  identités trigonométriques, chiffres romains
- **Physique et chimie** : chute libre, projectile, loi de Newton, gaz parfaits, Bernoulli, ondes, masse molaire,
  tableau périodique, potentiels redox
- **Santé** : IMC, métabolisme de base, masse grasse
- **Dates** : écart entre deux dates, date de Pâques
- **Fiches de référence** : unités, préfixes et constantes SI, brochages de composants et de connecteurs, boîtiers,
  symboles électroniques, portes logiques, calibres de fils, tableaux ASCII, codes HTTP, ports TCP/UDP, alphabets grec
  et OTAN, code Morse, aide-mémoire Git, regex, LaTeX et Markdown, spectre électromagnétique, propriétés des matériaux,
  perçage avant taraudage, roulements

## Technique

- **Langage** : [Kotlin](https://kotlinlang.org/)
- **Interface** : [Jetpack Compose](https://developer.android.com/jetpack/compose) et [Material 3](https://m3.material.io/)
- **Architecture** : MVVM, injection de dépendances avec Hilt, persistance avec Room
- **Navigation** : Navigation Compose
- **Cible** : Android 6.0 (API 23) à Android 15 (API 35)

## Installation pour le développement

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/astraeos-dev/Ganymede.git
   ```
2. Ouvrir le dossier dans Android Studio (dernière version stable) et laisser Gradle se synchroniser.
3. Lancer l'application sur un émulateur ou un appareil.

Pour utiliser Firebase (Crashlytics…), ajouter votre propre fichier `google-services.json` dans `app/`.

## Documentation

- [`REFACTORING.md`](REFACTORING.md) : refonte de l'architecture (Hilt, Room, MVVM)
- [`directory_structure.md`](directory_structure.md) : organisation des dossiers

## Contribuer

Les suggestions et corrections sont les bienvenues : ouvrez une issue ou une pull request.

## Licence

Projet distribué sous licence MIT : voir le fichier [`LICENSE`](LICENSE).
