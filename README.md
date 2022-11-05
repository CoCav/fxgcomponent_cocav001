# Librairie de composants REACT
***

## Collaboration

Ce projet a été créé par CoCav et blCav.

## Description

Pour répondre à la demande de notre client, une bibliothèque de composants web réutilisable a été créée.

Elle comporte 11 composants déclinés chacun en 3 stories. 

Liste des composants : 

* Accordion
* Avatar
* Breadcrumbs
* Button : ButtonSize & ButtonVariant
* Card
* Divider
* Popover
* Textfield : TextField & TextFieldVariant

Bonus :
* Collection

## Détail des composants

**Accordion**
<br/><br/>Propriétés à changer :
* bordered (type boolean) : permet de changer l'aspect visuel de l'accordéon en y ajoutant des bordures ou non. 
* show (type boolean) : permet de garder ouvert ou non le tiroir d'un accordéon.
* item (type string) : permet d'inscrire le numéro du tiroir que l'on souhaite voir ouvert dans l'accordéon.
-----
**Avatar**
<br/><br/>Propriétés à changer :
* width (type number) : permet de définir la largeur d'une image.
* height (type number) : permet de définir la hauteur d'une image.
* alt (type string) : permet d'ajouter un texte alternatif lié à l'image.
* url (type string) : permet d'ajouter le chemin du fichier qui contient l'image. 
-----
**Breadcrumbs**
<br/><br/>Propriétés à changer :
* separator (type string) : permet de changer l'aspect visuel des séparateurs entre les liens ("/", "-" ou "|").
* url (type string) : permet d'ajouter l'url des liens.
* item (type number) : permet de définir le nombre maximal de liens à afficher à l'écran.
-----
**ButtonSize**
<br/><br/>Propriétés à changer :
* size (type string) : permet de définir la taille du bouton (small, medium ou large).
* label (type string) : permet de définir le texte du libellé du bouton.
-----
**ButtonVariant**
<br/><br/>Propriétés à changer :
* variant (type string) : permet de définir l'aspect visuel du bouton (contained, outlined ou text).
* label (type string) : permet de définir le texte du libellé du bouton.
-----
**Card**
<br/><br/>Propriété à changer :
* title (type string) : permet de définir le titre de la carte.
* size (type string) : permet de définir la taille de la carte (small ou default).
-----
**Divider**
<br/><br/>Propriétés à changer :
* orientation (type string) : permet de définir l'orientation de la barre de séparation (left, right ou center).
* text (type string) : permet de définir un texte qui accompagne la barre de séparation.
-----
**Popover**
<br/><br/>Propriétés à changer :
* trigger (type string) : permet de définir le type d'événement qui fera apparaître le menu (hover, focus ou click).
* label (type string) : permet de définir le texte du libellé du bouton.

-----
**TextField**
<br/><br/>Propriétés à changer :
* id (type string) : permet de définir l'id du champ.
* label (type string) : permet de définir le libellé du champ.
* placeholder (type string) : permet de définir le texte du placeholder du champ.
* LabelTextHelper (type string) : permet de définir le texte du texthelper du champ.
-----
**TextFieldVariant**
<br/><br/>Propriétés à changer :
* id (type string) : permet de définir l'id du champ.
* label (type string) : permet de définir le texte du libellé du champ.
* placeholder (type string) : permet de définir le texte du placeholder du champ.
* variant (type string) : permet de définir l'aspect visuel du bouton (filled, outlined ou standard).

-----
**Collection**
<br/><br/>Propriétés à changer : imageurl : type array, width : type number
* imageurl (type array) : permet d'ajouter des images dans un tableau.
* width (type number) : permet de définir la largeur des images contenues dans le tableau.


## Langue

Ce projet a été réalisé en anglais.

## Technologies
Langage utilisé :
* React (https://fr.reactjs.org/): version 17.0.2

Librairies open source externes utilisées :
* Storybook (https://storybook.js.org/): version 6.5
* MUI (https://mui.com/): version 5.10.9
* Ant Design (https://ant.design/): version 4.23.5

### Pour démarrer le projet :

```sh
yarn install
```

```sh
yarn storybook
```
