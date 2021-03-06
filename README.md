# <img src="logo.png" alt="class logo" class="logo"/> Bases de données avancées

* **Cours:** [M3106](http://cache.media.enseignementsup-recherche.gouv.fr/file/25/09/7/PPN_INFORMATIQUE_256097.pdf)
* **Responsable:** Sébastien NEDJAR, [sebastien.nedjar@univ-amu.fr](mailto:sebastien.nedjar@univ-amu.fr)
* **Enseignants:** [Sébastien NEDJAR](mailto:sebastien.nedjar@univ-amu.fr)
* **Besoin d'aide ?**
    * La page [Piazza de ce cours](https://piazza.com/univ-amu.fr/spring2017/m2105/home).
    * Consulter et/ou créér des [issues](https://github.com/IUTInfoAix-M3106/Syllabus/issues).
    * [Email](mailto:sebastien.nedjar@univ-amu.fr) pour une question d'ordre privée, ou pour convenir d'un rendez-vous physique.

## Intentions pédagogiques
Appréhender des notions avancées sur la qualité des schémas et les aspects systèmes.

## Pré-requis
- **M2106** : Programmation et administration des bases de données

## Objectifs du parcours
- Qualité des schémas, problème de la redondance, formes normales
- Contraintes d’intégrité et règles de gestion, déclencheurs
- Présentation de l’architecture fonctionnelle d’un système de gestion de bases de données (SGBD)
- Transactions, atomicité et gestion de la concurrence d’accès
- Optimisation : index, requêtes et plan d’exécution
- Liens avec les langages de programmation 

## Contenu et structuration du parcours

### CM (4h)
#### Séance 1 : [Découverte de JDBC](https://github.com/IUTInfoAix-M3106/CoursJdbc)
#### Séance 2 : [Découverte de JPA2](https://github.com/IUTInfoAix-M3106/CoursJpa)

### TD
#### Séance 1 : Mise en place de l'environnement
- Mise en place d'une base de données
- Compréhension de Maven
- [Découverte d'un exemple simple d'interrogation avec JDBC](https://github.com/IUTInfoAix-M3106/TutoJDBC)

#### Séance 2 et 3 : Tp d'initiation à JDBC
- Concept de base
- Écriture des entités
- [Création du couche de persistance avec JDBC](https://github.com/IUTInfoAix-M3106/TpJDBC)

#### Séance 4 et 5 : Tp d'initiation à JPA
- [Découverte de JPA](https://github.com/IUTInfoAix-M3106/TutoJPA)
- [Création du couche de persistance avec JPA](https://github.com/IUTInfoAix-M3106/TpJpa)

## Méthodologie
Formation-action participative et interactive : ces formations s'appuient sur les connaissances, les expériences des participants, leur implication les rendant acteurs de leur formation. Alternance d'apports théoriques, réflexions collectives et individuelles, mises en situation par des exercices et des réalisations pratiques.

## Supports pédagogiques
Les supports pédagogiques seront mis à disposition des étudiants directement sur [l'organisation Github de cet enseignement](https://github.com/IUTInfoAix-M3106). 

## Ressources humaines et techniques
Les membres de l’équipe conçoivent et animent les formations. Les équipements et matériels disponibles au département informatique de l'IUT d'Aix-Marseille seront utilisés pour illustrer les apports et pour concrétiser certaines réalisations.

Pour travailler sur d'autres machines que celle du département, il faudra installer les outils suivants : 
- [Java SE Development Kit 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven](https://maven.apache.org/)
- [Git](https://git-scm.com/)
- [Bash](https://www.gnu.org/software/bash/) et/ou [Zsh](http://ohmyz.sh/)
- Un IDE Java ([Eclipse](http://www.eclipse.org/downloads/packages/eclipse-ide-java-developers/keplersr1), [Netbeans](https://netbeans.org/downloads/) ou [IntelliJ](https://www.jetbrains.com/idea/))

L'installation de ces outils peut se faire manuellement sous windows, avec [homebrew](https://brew.sh/index_fr.html) sous MacOS ou avec le gestionnaire de paquet de votre distribution Linux.

## Modalités d'évaluation
L'évaluation sera double. Elle sera constitué d'un examen sur table de 2h et d'un Tp noté

