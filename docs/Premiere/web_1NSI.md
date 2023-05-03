# Créer ses propres pages web

## 1) Introduction

Nous consultons tous les jours des sites Web. Pour les sites les plus connus, on peut s’apercevoir que l’affichage et les fonctionnalités sont identiques quel que soit le navigateur utilisé (ce n’est pas toujours le cas pour des sites moins connus) à quelques détails près.

Les pages Web sont créées à l’aide de langages informatiques. Le respect des règles définiespour ces langages permet de créer des pages WEB qui pourront être lues correctement quel que soit le navigateur.

Pour créer la page Web visualisée, ont été utilisés les langages HTML et CSS. Le langage HTML a été créé en 1991 par Tim Berners-Lee. Ce dernier a aussi créé le World Wide WebConsortium (W3C) qui définit les nouvelles versions et les standards des langages liés au Web.

## 2) Créer ses propres pages web

### 2.1) HTML et éditeurs

Pour créer des pages Web, on peut utiliser:

- Des logiciels WYSIWYG (What You See Is What You Get); ce sont des programmes(Mozilla Composer, Dreamweaver et même les traitements de texte) qui permettent de créer des sites sans apprendre de langage particulier. Les pages web sont générés automatiquement. Permettant une création plus rapide au démarrage, ils présentent cependant l’inconvénient de modifications plus laborieuses (le codage n’est pas optimisé,rendant toute modification problématique)
- Des éditeurs de texte, ce sont des programmes dédiés à l'écriture de code (pas seulement HTML ou CSS) plus ou moins évolués (les fonctionnalités de certains facilitent l'écriture du code). Nous utiliserons l'éditeur de texte Visual Studio Code Pour télécharger ce logiciel, il faut se rendre à l’adresse suivante : [https://code.visualstudio.com](https://code.visualstudio.com/)

### 2.2) Ma première page

- Dans vos documents, créer un dossier nommé *monPremierSite*. Puis dans ce dossier, créer à nouveau un dossier nommé *img* pour les images.

- Ouvrir *Visual Studio Code* et créer un nouveau document. Pour cela, il faut cliquer sur File dans la barre d’outil puis *New File*>.

- Puis saisir le code suivant (ou bien faites un Copier/Coller à partir du TP ) :

    <p class="codepen" data-height="367" data-theme-id="dark" data-default-tab="html,result" data-user="ga78523"
            data-slug-hash="wvJQqyv"
            style="height: 367px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;"
            data-pen-title="FirstPage">
            <span>See the Pen <a href="https://codepen.io/ga78523/pen/wvJQqyv">
                    FirstPage</a> by eric (<a href="https://codepen.io/ga78523">@ga78523</a>)
                on <a href="https://codepen.io">CodePen</a>.</span>
        </p>
        <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

- Enregistrer votre fichier sous le dossier *monPremierSite* sous le nom de : pageWeb1.html. Bien vérifier, que l’extension de votre fichier est .html et non .txt Sous *Visual Studio Code*, les balises apparaissent en bleu, les commentaires en vert et le texte visible par l’utilisateur en blanc. Si vous ne voyez pas cette coloration syntaxique, appeler le professeur.

- Une fois enregistré votre travail, ouvrir votre fichier pageWeb1.html avec un navigateur internet (Firefox, Chrome, Explorer ...)

- Modifier le code précédent pour obtenir ceci:

![page1](https://ga78523.github.io/site_cours/NSI/CoursPremierePdf/web/1PageModifiee.png)

### 2.3) Le langage HTML

Le langage HTML (HyperText Markup Language) permet de concevoir des documents Web. Ce langage de programmation descriptif est composé d'éléments. Un élément HTML est composé d'une balise ouvrante et d'une balise fermante afin de délimiter la zone de texte concernée par l'élément en question.

Par exemple, l'élément p, que nous avons utilisé délimite un paragraphe de texte, a pour balise ouvrante <p> et pour balise fermante </p>. Il y a également la balise <!DOCTYPE html>. Le doctype (pour Document Type Declaration) permet de renseigner le navigateur Web sur la version de HTML utilisée par le document Web. Le doctype utilisé dans l'exemple fait référence à HTML5. Un fichier HTML est composé de deux parties.

<head> et </head> : les éléments contenus dans l'entête n'ont pas vocation à être affichés sauf l'élément title dont le contenu apparaît dans l'onglet du navigateur Web. Les informations contenues dans l'entête renseignent sur l'auteur et le contenu du document.

<body> et </body>: l'ensemble des informations contenues entre ces balises sont affichées dans la fenêtre du navigateur Web.

### 2.4) Structuration des documents

- Titre de section : les balises h1, h3, h3, h4, h5, h6 permettent de définir des titres de sections, sous-sections, etc jusqu’à six niveaux.

- Balises de texte :

| Balises             | Rôle             |
| ------------------- | ---------------- |
| <b > et </b >       | Mise en gras     |
| <i > et </i >       | Mise en italique |
| <u > et </u >       | soulignement     |
| <sub > et </sub >   | mise en indice   |
| <sup > et </sup >   | mise en exposant |
| <code > et </code > | code             |
| <mark > et </mark>  | texte surligné   |

- Structuration du document. La balise <p> représente un paragraphe. Les espaces et les retours à la lignes sont ignorés. Chaque nouvel élément p crée un nouveau paragraphe.
- Dans la balise body, on peut placer l’attribut bgcolor="# 33CCFF". Celui-ci permet de colorer le fond d’écran d’une certaine couleur (ici: le bleu clair). Attention: la couleur est écrite en hexadécimal. Cela nous donne:

### 2.5) Travail à faire

1. Rechercher sur internet et écrire ci-dessous, le code hexadécimal du:
- du blanc : ...........

- du vert : ...........

- du rouge : ...........

- du jaune: ...........

- du magenta : .........

- du cyan : ..........

- du gris foncé : ......
3. Réaliser une page internet qui se nommera *pageWeb2* et qui ressemble à celle ci-dessous avec :
   - un titre ;
   - deux paragraphes écrits séparé par un ligne ;
   - un fond d’écran de couleur gris ;
   - un mot mis en évidence.

Remarque: pour créer un paragraphe imaginaire, vous pouvez utiliser le site [Lorem ipsum](http://fr.lipsum.com/). En effet, on sait depuis longtemps que travailler avec du texte lisiblee t contenant du sens est source de distractions, et empêche de se concentrer sur la mise en page elle-même.

### 2.6) Les images

On peut insérer une image (au format png, jpeg ou gif) qui se trouve sans le dossier *img* du dossier *monPremierSite* grâce à la balise <img > . Donc pour insérer une image (smiley.gif préalablement enregistrée dans le dossier *img*), on peut procéder de la manière suivante : 

"""
< img src="Img/smiley.gif" alt="Smiley face" width="42" height="42" >
"""


Détaillons cette ligne:

- src="smiley.gif" donne le nom de la photo à afficher (smiley.gif). Cet attribut est obligatoire.
- alt="Smiley face" spécifie un texte alternatif si l’image ne s’affiche pas (Smiley face). Cet attribut est recommandé.

### 2.7) Les liens

HTML (Hyper Text Markup Language) est un langage hypertexte, cela signifie qu'il vous permet en cliquant sur un mot, généralement souligné (ou une image) de vous rendre :

- sur un autre endroit de la page ;
- sur un autre fichier HTML situé sur votre ordinateur.
- sur un autre ordinateur en réseau, y compris sur le Web.

Pour écrire un lien sur une page web, il faut adopter la syntaxe suivante: < a href="lien"> texte <\a> avec:

- texte: texte qui apparaît en bleu souligné dans la page
- lien: adresse d’un site site (Exemple : https://fr.wikipedia.org/wiki/Informatique) , d’une autre page html située dans notre dossier monPremierSite (exemple: pageWeb3.html à créerultérieurement) ou bien un mot dans la page web concernée. Exemple: voir code et résultat précédents

### 2.8) Travail à faire

Réaliser deux pages internet qui ont chacune :

- Un titre ;
- Deux paragraphes ;
- Une image de 300 pixels de largeurs entre les deux paragraphes et la même image àla fin ;
- Un fond d’écran de couleur ;
- Un lien pour l’autre page et un lien vers un fichier existant.

### 2.9) Les listes

On peut organiser le texte en liste. Une liste énumérée est contenue dans un élément ol (abréviation de l’anglais ordered list). Une liste non-énumérée est contenue dans un élément ul (abréviation de l’anglais unordered list). Quelque soit le type de liste, chaque entrée de liste est contenue dans un élément li. Les listes peuvent évidemment être imbriquées

![travail](https://ga78523.github.io/site_cours/NSI/CoursPremierePdf/web/travailFaire.png)

### Pour en savoir plus...

Pour connaître d’autres balises et d’autres attributs, consulter le site MDN.

## 3) Le CSS (Cascading Style Sheets)

### 3.1) Introduction

Vous avez remarqué que si nous voulons donner une unité au site, il est nécessaire, pour chaque page, de définir par exemple une police bleue.

![CSS](https://ga78523.github.io/site_cours/NSI/CoursPremierePdf/web/css1.png)

Or, nous pouvons aussi utiliser une page de style écrite dans un autre langage: le CSS. Le Langage CSS, apparu en 1996, est complémentaire du langage HTML et permet de gérer la mise en forme (l'apparence) des différentes pages d’un site Web (couleur du texte, police, taille du texte, bordures, fond...)

Ainsi, dans l’exemple précédent, il suffit de créer une page style.css (avec Visual StudioCode par exemple) dans laquelle il écrit que les paragraphes sont en bleu. Toutes les pages html créées appelleront *style.css* dans l’en-tête (head) de la page grâce à l’instruction : 

```html
<link href="style.css" rel="stylesheet" type="text /css">
```

![CSS](https://ga78523.github.io/site_cours/NSI/CoursPremierePdf/web/utiliteCSS.png)

### 3.2) Explications

Ici, on indique que l’élément p (paragraphe) contient du texte aligné des deux côtés (justifié) et de couleur bleue. On indique également que l’élément body (corps de la page HTML) aura un fond d’écran couleur gainsboro c’est-à-dire bleu très clair.

En CSS:

- Body et p sont nommés selecteur
- color, text-align, background-color sont nommés propriétés CSS
- gainsboro, blue, justify sont nommés valeurs

### 3.3) La notion de boite

Dans le modèle des feuilles de style, tous les éléments d’une page HTML se coulent dans des blocs (ou «boites») rectangulaires. Un bloc typique est représenté ci-dessous :

![CSS](https://ga78523.github.io/site_cours/NSI/CoursPremierePdf/web/boite.png)

A partir de l’extérieur, on rencontre successivement 4 zones:

- Une marge externe (margin), toujours transparente, avec des épaisseurs réglables côté par côté ;
- Une bordure (border) dont on peut régler l’épaisseur, la couleur et le style côté par côté ;
- Une marge interne (padding), ou «espacement», d’épaisseur réglable côté par côté ;
- L’espace dévolu au bloc Il existe en HTML deux catégories d’éléments textuels : les éléments block (les éléments p, ul sont par défaut des éléments block) qui créent une boite et forcent un retour à la ligne et les éléments de type inline (les éléments a, b, i sont par défaut des éléments inline) qui placentleur contenu dans le flot du texte.

Il est possible faire passer des éléments inline en éléments block(et inversement à l’aide de la propriété display.

### 3.4) Quelques propriétés CSS

De nombreuses propriétés CSS indiquent des longueurs (taille d’une bordure, d’un ajustement, taille des polices). Leur valeur est toujours un nombre suivi d’une unité. Parmi les unités légales en CSS, on retrouve notamment le pixel (px) et le point (pt). Nous donnons ci-dessous quelques propriétés CSS.

| Propriété       | Valeur                                                               | Description                                                                                                                          |
| --------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| display         | None, block ou inline                                                | mode d’affichage de la boîte                                                                                                         |
| Background      | couleur                                                              | couleur de fond de la boîte                                                                                                          |
| color           | couleur                                                              | couleur de texte                                                                                                                     |
| border          | taille motif couleur ou none                                         | Si none, la bordure est masquée. Sinon, on donne la taille, le motif (solid, dotted oudashed) et la couleur séparés par des espaces. |
| margin          | longueur                                                             | taille des marges                                                                                                                    |
| padding         | longueur                                                             | taille des ajustements                                                                                                               |
| text-decoration | none, underline, overline, ouline-through                            | décoration du texte                                                                                                                  |
| text-align      | left, right, ou justify                                              | justification du texte                                                                                                               |
| font-family     | fixed, serif, ou sans serif                                          | justification du texte                                                                                                               |
| font-weight     | normal, light, bold, ou bolder                                       | graisse de la police                                                                                                                 |
| font-style      | normal ou italic                                                     | style de la police                                                                                                                   |
| font-size       | Longueur ou xx-small, x-small,small, normal, large, x-large,xx-large | taille de la police                                                                                                                  |

### 3.5) Les balises div et span et les class

Les éléments div sont des balises de type bloc tandis que les éléments span sont des balises de types inline. Elles sont surtout utiles pour "déconnecter" certains morceaux de paragraphe ou plusieurs paragraphes de cette logique d'écriture avec des feuilles de style. Elles créent ainsi des petits blocs particuliers dans le document sans devoir repasser par les éléments structurels du Html classique. Les attributs class et id sont des attributs universels ce qui signifie qu’on va pouvoir les utiliser avecn’importe quel élément HTML, et notamment avec les éléments div et span.En pratique, il va être très courant de préciser des attributs class et id pour nos éléments div et span pour pouvoir appliquer des styles à un div (ou span) ou à un groupe d’éléments div ou span) définis.

### 3.6) Les tableaux

On peut enfin organiser du texte dans des tableaux au moyen de l’élément table, qui contient l’ensemble des lignes du tableau, chacune d’elle consistant en un élément tr (abréviation del’anglais table row). Enfin chaque ligne décrit les cases qu’elle contient au moyen de l’élément td.

### 3.7) Pour en savoir plus...

Vous pouvez aller sur le site W3S où il existe un validateur HTML5 et sur le site de Pierre Giraud ([site](https://www.pierre-giraud.com/html-css-apprendre-coder-cours/introduction/) ).
