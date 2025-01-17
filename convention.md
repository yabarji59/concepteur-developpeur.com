## Tables des matières 
<!-- TOC -->
* [Dans quel but ?](#dans-quel-but)
* [Les différentes conventions :](#diff)
<!-- TOC -->

# Dans quel but ? 

Il existe plusieurs façons d'écrire un même code. De manière à uniformiser le code de différents développeurs dans les entreprises, des **conventions** existent. Ces conventions permettent aux développeurs d'une équipe de rendre un code uniformisé, compréhensible par tous. 

Les conventions couvrent différents domaines :

- Style d'indentation
- convention de nommage et d'organisation des fichiers (architecture projet)
- commentaire et documentation du code source 
- déclaration des variables

Dans ce cadre, les **linters** et **formatteurs** permettent de "modifier" un code source afin d'en rendre une version claire.

Suivre ces règles de convention apporte différents avantages : 

- Une meilleure maintenance logicielle (40 à 80 % de réduction du coût de maintenance)
- Améliore la lisibilité du code pour d'autres ingénieurs logiciel et rends plus facile le peer review. 

<br/>

# <a name = "diff" ></a>Les différentes conventions: 

Les plus grandes compagnies ont sorti leurs conventions respectives concernant Javascript :

* **Standard Style Guide **: Contient un linter et un formatter, suivi par Github, NPM, Heroku, MongoDB. De plus en plus utilisé dans l'OpenSource.
    - Pas de configuration, simple à utiliser et suivre.
    - Formatter automatiquement le code
    >https://github.com/standard/standard_

* **Google Style Guide** : Google a sorti un guide pour Javascript, mais également pour HTML / CSS / C++ / TypeScript ou Angular. 
    - Fourni avec ESLint 
   > https://google.github.io/styleguide/

* **Airbnb Style Guide**: Un des plus populaires. Très complet, des objets au testing. Propose des conventions CSS, JS, Ruby et React. Il est apprécié pour ça :
    - Consistence
    - lisibilité
    - Prédictibilité
    - Efficacité 
     
    > https://github.com/airbnb/javascript

* **Clean Code Style Guide**: Tiré du livre de Robert C. Martin, les principes de ce livre ont été repris et appliqués au Javascript. C'est une liste de bonnes pratiques pour une écriture lisible du JavaScript. 
    > https://github.com/ryanmcdermott/clean-code-javascript



**_Nous faisons le choix de suivre la convention proposée par AirBnb dans une stack JavaScript._**