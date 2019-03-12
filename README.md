# Html, Css & Responsive Web Design
<img src="https://r.hswstatic.com/w_907/gif/tesla-cat.jpg"  width="500"/>

## Entrée en matière:
**Un outil pour éditer votre contenu: Visual Studio Code**

### Basic editing: Les astuces

- **Ctrl+X** Cut line (empty selection)
- **Ctrl+C** Copy line (empty selection)
- **Alt+ ↑ / ↓** Move line up/down
- **Shift+Alt + ↓ / ↑** Copy line up/down
- **Ctrl+Shift+K** Delete line
- **Ctrl+Enter** Insert line below
- **Ctrl+Shift+Enter** Insert line above
- **Ctrl+] / [** Indent/outdent line
- **Home / End** Go to beginning/end of line
- **Ctrl+Home** Go to beginning of file
- **Ctrl+End** Go to end of file
- **Ctrl+↑ / ↓** Scroll line up/down
- **Alt+PgUp / PgDn** Scroll page up/down
- **Ctrl+Shift+[** Fold (collapse) region
- **Ctrl+Shift+]** Unfold (uncollapse) region
- **Ctrl+K Ctrl+[** Fold (collapse) all subregions
- **Ctrl+K Ctrl+]** Unfold (uncollapse) all subregions
- **Ctrl+K Ctrl+0** Fold (collapse) all regions
- **Ctrl+K Ctrl+J** Unfold (uncollapse) all regions
- **Ctrl+K Ctrl+C** Add line comment
- **Ctrl+K Ctrl+U** Remove line comment
- **Ctrl+/ Toggle** line comment
- **Shift+Alt+A** Toggle block comment
- **Alt+Z** Toggle word wrap

## Semaine 2: un nouveau cours pour une nouvelle vie!

**HTML**: HyperText Markup Language (Language de balise, pour structurer la page)
**CSS**: Cascading Style Sheets (Mise en page, visuel)

### Vos meilleurs amis:
- https://www.w3schools.com/html/default.asp
- https://developer.mozilla.org/fr/docs/Web/HTML

# **HTML**
### Page type:

![alt text](https://image.noelshack.com/fichiers/2019/11/1/1552294998-capture.png)

- **```<!DOCTYPE html>```** : type de contenu
- **```<html>```**: va définir la racine, une seule
- **```<head>```**: Tête du document, infos, titre du document, lien vers le CSS, metadonnées...
- **```<inline>```**: Ne pertube pas l'élément parent, prend la largeur nécéssaire (ex: la balise p)
- **```<block>```**: Prend la largeur du conteneur (ex: la balise div)
- **```<header>```**: indique l'entête
- **```<nav>```**: le menu de navigation
- **```<main>```**: contenu du site
- **```<aside>```**: complément d'information
- **```<article>```**: Corps d'une partie d'article
- **```<section>```**: Va être contenu dans l'article
- **```<footer>```**: indique le pied de page du site
- **```<p>```**: pour les paragraphe (le reste étant par exemple des titres: **```<h1>```**
- **```<a href="www.monadresse.fr>Text descriptif</a>```**: lien hypertext
- **```<img src="" alt"">```**: pour intégrer un image
- **```<figure><figcaption>Description de l'image</figcaption></figure>```**: les éléments ```<figure>``` et ```<figcaption>``` fonctionnent de concert pour associer une légende à une illustration ou un autre élément média
- **```<video width="320" height="240" controls></video>```**: pour intégrer un image
- **exemple**:  ```<video width="320" height="240" controls> <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4"> <source src="movie.ogg" type="video/ogg"></video>```
- **``<iframe>``**: ```<iframe width="560" height="315" src="https://www.youtube.com/embed/nIshgLfQWec" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>```
- **``<form>``**: ```<form action="" method=""></form>```: deux méthodes 1/ GET et 2/ URL
- **la balise ```<form>```**: la balise formulaire
 - **Exemple**: 
 
![alt text](https://image.noelshack.com/fichiers/2019/11/1/1552313355-capture2.png)


### Les tableaux

- L'élément **``<table>``** correspond au tableau lui-même
- L'élément **``<tr>``** est utilisé pour définir chacune des lignes du tableau
- L'élément **``<td>``** est utilisé pour chaque cellule
- colspan
Indique que la cellule courante s'étend sur plusieurs colonnes.
- rowspan
Indique que la cellule courante s'étend sur plusieurs lignes.
- nowrap
Empêche les sauts de lignes à l'intérieur de la cellule courante.
- L'élément **``<th>``** permet de définir des cellules d'entête. Les navigateurs visuels par exemple utilisent cette information pour mettre ces cellules en gras
- L'élément **``<caption>``** permet de placer une légende au-dessus ou au-dessous d'un tableau 

# **CSS**

Les feuilles de style en cascade, généralement appelées CSS de l'anglais Cascading Style Sheets, forment un langage informatique qui décrit la présentation des documents HTML et XML. Les standards définissant CSS sont publiés par le World Wide Web Consortium (W3C).

### Les sélecteurs

Exemple d'appel:

![alt text](https://image.noelshack.com/fichiers/2019/11/1/1552319808-capture4.png)
![alt text](https://image.noelshack.com/fichiers/2019/11/1/1552319947-capture5.png)

### Les unités de mesure
- **des indications ici: https://www.w3.org/Style/Examples/007/units.fr.html**
##### Les tailles recommandées: px, em, %:
- **L'unité em**: se rapporte à la taille de la police. Avec elle on peut affecter une mesure relative à la taille de police de l'élément parent. Elle permet d'avoir des feuilles de style plus facilement adaptables d'un média à un autre. Les nombres décimaux sont autorisés, mais il faut tout simplement remplacer la virgule par un point. Cette valeur em est utilisable pour d'autres propriétés acceptant la mention de longueur.
- **L'unité px**: l'écran d'un ordinateur ou moniteur est formé par plusieurs petits "carrés". Ces carrés définissent la résolution ou densité de l'écran en pixels d'affichage selon l'unité de sortie, c'est-à-dire l'écran de l'ordinateur. L'unité px qui veut dire pixel correspond à un de ces petits carrés.
- **L'unité de %**: s'exprime en %...

### Les pseudo-classes
Une pseudo-classe est un mot-clé qui peut être ajouté à un sélecteur afin d'indiquer l'état spécifique dans lequel l'élément doit être pour être ciblé par la déclaration. La pseudo-classe :hover est un bon exem
- **c'est ici: https://developer.mozilla.org/fr/docs/Web/CSS/Pseudo-classes** <br/>
``sélecteur:pseudo-classe {`` <br/>
 ``propriété: valeur;``<br/>
``}``

#### Exemple d'intervention: sur les liens:
- a:link - a normal, unvisited link (de base: avec a { })
- a:visited - a link the user has visited
- a:hover - a link when the user mouses over it
- a:active - a link the moment it is clicked

- **Pour essayer: https://www.w3schools.com/css/css_link.asp**

### Best Practice

Pensez a bien respecter la nomenclature, je vous propose celle-ci:
- HTML:```<div class="my-string">``` [hyphens]
- CSS: ```.my-string``` [hyphens]
- Javascript: ```var myString = ''```; [camelCase]
- PHP: ```$My_String = ''```; [underscores]


  
