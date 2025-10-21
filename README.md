[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/7OjGO36a)
# Introduction à Spark

## Installation de Spark et du projet
Pour pouvoir exécuter les exemples de ce projet, il faut disposer d'un environnement Spark/Jupyter.
Pour cela, vous pouvez utiliser `pyspark` avec un environnement virtuel Python.
**Vous devez également disposer d'un JRE (ou d'un JDK) sur la machine.**

```bash
python3 -m venv sparkenv # Création d'un environnement virtuel
source sparkenv/bin/activate # Activation de l'environnement
python3 -m pip install -r requirements.txt # Installation des bibliothèques (pyspark, ...)
```

## Utilisation du projet
Avant de lancer `pyspark` ou un notebook, il faut activer l'environnement virtuel créé ci-dessus.

```bash
source sparkenv/bin/activate # Activation de l'environnement
```

## Construction du support de cours
Les slides sont au format [asciidoctor](http://asciidoctor.org/).

```bash
bundle install
bundle exec rake
```

## Mettre à jour le projet
* Les versions de [`asciidoctor`](https://asciidoctor.org/) sont configurables dans [`Gemfile`](./Gemfile) (cf. [rubygems.org](https://rubygems.org/?locale=fr))

```bash
bundle update --bundler
bundle update
```
