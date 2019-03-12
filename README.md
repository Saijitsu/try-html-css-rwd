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


### __Les tableaux__

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

### __Les sélecteurs__

Exemple d'appel:

![alt text](https://image.noelshack.com/fichiers/2019/11/1/1552319808-capture4.png)
![alt text](https://image.noelshack.com/fichiers/2019/11/1/1552319947-capture5.png)

### __Les unités de mesure__

- **des indications ici: https://www.w3.org/Style/Examples/007/units.fr.html**

##### Les tailles recommandées: px, em, %:
- **L'unité em**: se rapporte à la taille de la police. Avec elle on peut affecter une mesure relative à la taille de police de l'élément parent. Elle permet d'avoir des feuilles de style plus facilement adaptables d'un média à un autre. Les nombres décimaux sont autorisés, mais il faut tout simplement remplacer la virgule par un point. Cette valeur em est utilisable pour d'autres propriétés acceptant la mention de longueur.
- **L'unité px**: l'écran d'un ordinateur ou moniteur est formé par plusieurs petits "carrés". Ces carrés définissent la résolution ou densité de l'écran en pixels d'affichage selon l'unité de sortie, c'est-à-dire l'écran de l'ordinateur. L'unité px qui veut dire pixel correspond à un de ces petits carrés.
- **L'unité de %**: s'exprime en %...

### __Les pseudo-classes__
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

### __Propriétés des boites:__

![alt text](https://mdn.mozillademos.org/files/16052/image_1.png) <br/>
**Le cours parfait ici:** https://developer.mozilla.org/fr/docs/Apprendre/CSS/Introduction_%C3%A0_CSS/Le_mod%C3%A8le_de_bo%C3%AEte

#### __La propriété margin__

On peut détailler les tailles des marges à l'aide des suffixes: <br/>
**top (haut)**,<br/>
**right (droite)**,<br/>
**bottom (bas)**,<br/>
**left (gauche)**, <br/>
Vous pouvez aussi synthétiser les quatre d'un seul coup (la première valeur étant celle du haut, puis on tourne dans le sens des aiguilles d'une montre).
**margin: 2px 5px 2em 0; <br/>
**revient à :** <br/>
margin-top: 2px;
margin-right: 5px;
margin-bottom: 2em;
margin-left: 0;

#### __La propriété border__

**L'essentiel et des exemples ici: https://developer.mozilla.org/fr/docs/Web/CSS/border**

#### __La propriété display__

**Votre cours ici: https://developer.mozilla.org/fr/docs/Web/CSS/display**
<br/>
La propriété display définit le type d'affichage utilisée pour le rendu d'un élément. Ce type d'affichage possède deux composantes : le type d'affichage extérieur qui définit comment la boîte participe au flux et le type d'affichage intérieur qui définit l'organisation des éléments enfants.

#### __La propriété position__

**Votre cours ici: https://developer.mozilla.org/fr/docs/Web/CSS/position**

#### __FLEXBOX c'est ici!__

Sommaire <br/>
1. justify-content
2. align-items
3. flex-direction
4. order
5. align-self
6. flex-wrap
7. flex-flow
8. align-content

**C'est ici! https://css-tricks.com/snippets/css/a-guide-to-flexbox/**
- Un petit tuto youtube ici (Grafikart): https://www.youtube.com/watch?v=LNqBKTeeiWo

**1. justify-content**<br/>

Utilisez encore justify-content pour aider ces grenouilles à se rendre à leurs nénuphars. Souvenez-vous que cette propriété CSS aligne les éléments horizontalement et accepte les valeurs suivantes :<br/>
<br/>
- **flex-start** : Les éléments s'alignent au côté gauche du conteneur.
- **flex-end** : Les éléments s'alignent au côté droit du conteneur.
- **center** : Les éléments s'alignent au centre du conteneur.
- **space-between** : Les éléments s'affichent avec un espace égal entre eux.
- **space-around** : Les éléments s'affichent avec un espacement égal à l'entour d'eux.
<br/>

**2. align-items** <br/>

Cette propriété CSS aligne les éléments verticalement et accepte les valeurs suivantes :<br/>


- **flex-start** : Les éléments s'alignent au haut du conteneur.
- **flex-end** : Les éléments s'alignent au bas du conteneur.
- **center** : Les éléments s'alignent au centre vertical du conteneur.
- **baseline** : Les éléments s'alignent à la ligne de base du conteneur.
- **stretch** : Les éléments sont étirés pour s'adapter au conteneur.

**3. flex-direction**<br/>

Cette propriété CSS définit la direction dans laquelle les éléments sont placés dans le conteneur, et accepte les valeurs suivantes :<br/>


- **row** : Les éléments sont disposés dans la même direction que le texte.
- **row-reverse** : Les éléments sont disposés dans la direction opposée au texte.
- **column** : Les éléments sont disposés de haut en bas.
- **column-reverse** : Les éléments sont disposés de bas en haut.

**4. order**<br/>

Dans ces cas, on peut appliquer la propriété order à des éléments individuels. Par défaut, les éléments ont une valeur de 0, mais on peut utiliser cette propriété pour changer la valeur à un entier positif ou négatif.<br/>


**5. align-self**<br/>

Une autre propriété que vous pouvez appliquer sur des éléments individuels est align-self. Cette propriété accepte les mêmes valeurs que align-items, mais s'applique seulement à l'élément ciblé.<br/>

- **flex-start**
- **flex-end**
- **center**
- **baseline**
- **stretch**

**6. flex-wrap**<br/>

La propriété flex-wrap, qui accepte les valeurs suivantes :<br/>


- **nowrap :** Tous les éléments sont tenus sur une seule ligne.
- **wrap :** Les éléments s'enveloppent sur plusieurs lignes au besoin.
- **wrap-reverse :** Les éléments s'enveloppent sur plusieurs lignes dans l'ordre inversé.

**7. flex-flow**<br/>

Les deux propriétés flex-direction et flex-wrap sont utilisées tellement souvent ensembles que le raccourci flex-flow a été créé pour les combiner. Ce raccourci accepte les valeurs des deux propriétés séparées par un espace.
Par exemple, vous pouvez utiliser flex-flow: row wrap pour configurer les colonnes et les faire s'envelopper.<br/>


**8. align-content**<br/>

Vous pouvez utiliser align-content pour définir comment plusieurs lignes sont espacées de l'une à l'autre. Cette propriété prend les valeurs suivantes :<br/>


- **flex-start :** Les lignes sont amassées dans le haut du conteneur.
- **flex-end:** Les lignes sont amassées dans le bas du conteneur.
- **center :** Les lignes sont amassées dans le centre vertical du conteneur.
- **space-between :** Les lignes s'affichent avec un espace égal entre eux.
- **space-around :** Les lignes s'affichent avec un espace égal autour d'eux.
- **stretch :** Les lignes sont étirées pour s'adapter au conteneur.

### __Grid: c'est ici!
<br/>
- Un tutoriel ic: https://la-cascade.io/css-grid-layout-guide-complet/ <br/>
La propriété grid est une propriété raccourcie qui permet de définir toutes les propriétés liées aux grilles CSS, qu'elles soient explicites (grid-template-rows, grid-template-columns et grid-template-areas), implicites (grid-auto-rows, grid-auto-columns et grid-auto-flow).


### __Best Practice__

Pensez a bien respecter la nomenclature, je vous propose celle-ci:
- HTML:```<div class="my-string">``` [hyphens]
- CSS: ```.my-string``` [hyphens]
- Javascript: ```var myString = ''```; [camelCase]
- PHP: ```$My_String = ''```; [underscores]

## Des chaînes YouTube à suivre pour vous auto-former:

- **Code et Design:** https://www.youtube.com/channel/UC9zdcXq2z3GY3UVhlADNijg
- **Grafikart:** https://www.youtube.com/channel/UCj_iGliGCkLcHSZ8eqVNPDQ

## Un site avec des tuto de qualité dans la langue de Molière:

- **Grafikart again! c'est ici: https://www.grafikart.fr**
  
