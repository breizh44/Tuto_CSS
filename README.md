# Tuto_CSS
Tutoriel CSS

Tutoriel issu de https://www.youtube.com/watch?v=iSWjmVcfQGg

Extension VScode utile : live server (permet de mettre à jour la page html en live dans le navigateur)

## Etape 1 : création du fichier index.html
- dans VScode, taper juste le caractère '!'. VScode doit vous proposer toute la structure HTML de base. Ou bien taper 'html:5' et VScode va vous proposer la structure de base HTML5.
- utiliser https://fonts.google.com/ pour trouver une jolie police (télécharger ou importer)

## Etape 2 : créer une div de classe "flexbox"
- pour créer une balise div portant la classe "flexbox", taper juste ".flexbox" dans VScode. VScode va générer automatiquement la div avec la classe.
- pour créer une balise de ul avec 3 sous balise li : taper "ul>li*3"
- installer le plugin rulerMeasurement dans chrome (pratique pour mesurer les dimensions sur la page HTML)

## Etape 3 : mise en place des flexboxs
- utilisation de display:flex (et paramétrage) pour gérer la répartition des éléments li

## Etape 4 : utilisation des grids pour un layout plus complexe
- création d'une balise div portant la classe "grid" (taper ".grid" dans VScode)
- puis création d'une sous balise portant la classe "grid-container"
- création d'une balise img dans la classe "grid-container"
- création d'un formulaire dans la classe "grid-container"
- mise en place d'une grille pour répartir horizontalement l'image et le formulaire

**Remarque :** par défaut la plupart des éléments HTML possèdent un display. Par défaut le display est block (div, h1, h2, ...) : on prend toute la largeur de la page et on renvoie à la ligne.