PARTOUT
	référer les figure
	les reference peuvent disparaitre




INTRO
motiver le problème (simule camera (jv) + fusion d’image + le pb n’est pas trivial (combine zoom avant/arrière))

analyse biblio
	impossibilité d’interplation (cf. ipol)
	zoom arrière zero-padding
	Ripmap/Mipmap

->revendication de methode
	toute homo
	decomp géométrique
	un peu plus lente




HOMOGRAPHIE
	va dans l’intro 5 ligne
	c’est un mvt d’une caméra idéal (cité david lowe pour stitching)

METHODE NAIVE
	mentionne dans l’introduction 


AFFINITE
	Theoreme 1 mis avec les schémas
	formule convolution discrète avec zoom (reference pseudo-code supp adaptatif)
	graphique avec le cosine weighted
	reference pseudo-code / figure (e.g. umax/vmax, transpoopt, dcompo affinite)
	prop 1 : Soit affine sous forme projective




MVT DE CAMERA
	mettre lemme plutôt que « finalement on en déduit »
	mettre des props / Lemme
	Prop 2 = revoir les notations (h ‘est’ un mvet de cam)

DECOMP HOMO
	include \begin{proof} \end{proof}

HOMO PARTICULIERE
	Rentrer « on en déduit » de fin de partie precedente, on le met là
	inclure image qui montre la séparation (damier par exemple)
	Lemme pour la convergence des convolées




//liste dégeux et incompréhensible de Jean-Thomas :
-permière page : auteur d'abord, direction en dessous.
-dans l'intro : analyse bibliographique.
-introduction : 1.phrases avec citation qui situe le sujet. On peut envisager réinterp. 
par spline si on fait un zoom-in (cite article Ipol sur interpspline)et zoom-out
(zero-padding) et combi rapide des des 2 méthodes (Mipmap, Ripmap) (Yaroslavsky ?).
		2.Le problème n'est pas trivial : il faut éviter le flou et l'aliasing.
Puis : dans cet article : nous pouvons traiter n'importe quelle homographie, basé sur analyse
géométrique, un peu plus lente que mipmap et ripmap.
		3.prés. plan
Intro : 1 pages au moins.

Les intérêt homographies : image stiching (davide lowe : automatic...image stiching......2007
) : rotation centre optique d'1 caméra (citer article panorama).

-méthode naïve : on peut le mettre dans l'introduction ( dire -> fort aliasing) (dire que l'on
va comparer avec notre méthode).
-ref au pseudo-code dans ripmap mipmap
-dans les images distance : mettre label.
-conclusion : la mettre de manière informelle.
-nous avons essayés et nous avons trouvé...
-mettre le thm à la fin de l'explication (szeliski)
-rajouter graphique tête du raised-cosined weighted
-on peut mettre : voir les détails du pseudo-code.
référence : <-> pseudo-code
- barre dans les matrice d'homographie : homogénéisé.
- en 21111 : "finalement on en déduit que" : mettre en Lemme
- mettre des : def, lemme < proposition < théorème
-21113 : mettre proposition
-ds le lemme : "sous les notations précédentes..."
-Proposition 2 : le mettre avant la démo... (rappeler les notations)
-pour les démo : "begin{proof}"..."end{proof}"
-article mathématique : pas de texte libre (disons presque pas...?)
-soit : notation, remarque





- mettre l'effet de h1 et h2 chaqun sur l'identité. (p 25)
- remarque : il faut que l'on puisse comprendre une phrase même si on enlève la référence

-231 : /sin /cos  pour bien mettre les cosinus et sinus.
- rms, l1 : begin{tab} end{tab} : mettre en gras les temps.
- pour les expérience : mettre les différence des images
- mettre expérience quand on fait pas bien les rotations avec les splines (ou même sans les splines)
- mettre : szelisky and ... (à côté de multi-étape).
-commande latex : clear float ou clear page : imprimme toutes les figure ...
-utiliser le même rescale pour chaque visualisation du spectre.
-mettre le moins de texte libre possible.


-mettre un conclusion : on propose une solution optimale dans le sens suivant. mipmap < decomposition 
pour des résultats super exacts.
ouverture dans la conclusion : on peut mettre surement plus rapide pour les rotations sans perdre trop
de qualité. 
//fin liste dégeux et incompréhensible de Jean-Thomas :
