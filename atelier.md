# Atelier présentation Mkdocs

## Prérequis installation 

* Un ordinateur équipé d'un interprète Python 3.x > 3.5 et la possibilité d'y installer des modules Python.

## Installation de mkdocs

```bash
pip3 install mkdocs-material
```

## Création nouveau site

```bash
cd /le/repertoire/racine/du/projet
mkdocs new .
```

## Éditer le site 

1. le fichier `mkdocs.yml`
2. la page d'accueil : `docs/index.html`

### Premiers changements

#### Ajout du thème `material` 

Dans `mkdocs.yml` ajouter les lignes suivantes :

```yaml
theme:
    name: material
```

#### Changement du titre du site

```diff
- site: My Doc
+ site: Casser un code de César
```

#### Éditer la page d'accueil

Remplacer le contenu par défaut du fichier `docs/index.html` par le **vrai** contenu...


### Ajout de fonctionnalités

### Navigation 

1. Limiter ce qui est rechargé à chaque changement de page :
   ```yaml
   theme:
       features:
           - navigation.instant
    ```
2. _tracking_
   ```yaml
   theme:
       features:
           - navigation.tracking
    ```
3. Les onglets de navigation dans le header :
    ```yaml
       theme:
           features:
               - navigation.tabs
    ```



## Idée exemples document

* Suites
* Monte-Carlo
* Fréquence apparition lettre
* dichotomie

## Fonctionnalités de base (langage markdown)

* Mise en forme titre
* Mise en forme texte
* Listes
* Liens
* Citations
* Icônes
* Images
* Tableaux

## Fonctionnalités avancées

### Intégration du code

### Intégration des maths

### Admonitions

### Onglets

### Mermaid


## Navigation

## Hébergement et mise en ligne

