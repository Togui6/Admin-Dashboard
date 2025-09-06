# Admin-Dashboard

Tip 1 : 
Pour increase ou decrease the size of an <img src="..."> il faut ajouter une classe à <img> et non au <div> qui l'englobe.
Ex : 
<img scr="..." class="lala">.
Ensuite sur CSS : 
.lala {
    width: 200%
}

OU BIEN
Utiliser ce CSS selector :
.div > img 
Et ça devrait marcher car l'on sélectionne directement <img>


Tip 2 :
Pour choisir la valeur de gras, au lieu d'utiliser <strong> ou <h1> <h2> etc... dans html,
on peut utiliser font-weight dans CSS 
Ex : 
.class_random {
    font-weight: 500;
}
400 = valeur initiale
700 = valeur de strong

Tip 3 :
Pour changer la couleur d'un SVG, il ouvrir le SVG par un lien google, si c'est un <img src>, ça va être plus compliqué.