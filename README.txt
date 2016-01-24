#############################################################################
#############################################################################
############                                                    ############# 
############     Logiciel de déssin automatique de barbules     ############# 
############       ou barbe de talus sur AutoCAD avec VBA       #############
############                                                    ############# 
############          Automatic bank drawing software           #############
############                  AutoCAD with VBA                  #############
############                                                    #############
############              GNU GENERAL PUBLIC LICENSE            #############
############               Version 3, 29 June 2007              ############# 
############                                                    #############
#############################################################################
#############################################################################
                                                             par/by flo_sto2f

			Français :

Voici les différentes étapes pour tracer vos barbules avec ce logiciel : 

	0 - Charger le logiciel (installer VBA préalablement)  à  l'aide de :
	Gérer/Applications/Charger un projet/.  Puis  lancer  la   commande :
	"-vbarun"
	puis inscriver
	"talus"

	1 - Cliquer sur "Sélectionner les lignes d'encadrement du talus" puis
	sélectionner  en  cliquant sur les objets du dessin représentant  les
	lignes haute et basse du talus.    

	2 - Renseigner  les  différentes  "Caractéristiques géométrique de la 
	barbule". La "Distance curviligne entre les lignes de liaisons"  doit
	être un nombre décimal  ou  entier positif. Le "Nombre d'espace entre 
	les  lignes  de  pente  par  motif"  doit  être  entier  et  naturel. 
	La  "Longueur des lignes de pentes"  doit  également être  un  nombre 
	décimal ou entier positif.    

	3 - Sélectionner  "Bloc"  ou  "Lignes"  pour obtenir les traits de la
	barbules en bloc ou en lignes. Si "Bloc" est sélectionner, renseigner
	également le nom du bloc dans lequel la barbule sera insérée.

	4 - Cliquer  sur  "Tracer la barbule"  pour tracer automatiquement la 
	babule.

Remarques : Plusieurs barbules peuvent être placées dans  un  même bloc mais, 
une unique insertion  de  ce  bloc sera réalisée. Les lignes haute  et  basse 
doivent  être  constituées  d'un  unique élement du dessin (ligne, polyligne,
spline, etc.).

			"Poor" english :

Here are the steps to draw banks using this software: 

	0 - Load the software (VBA must be installed) then run  the  command:
	"-vbarun"
	and write 
	"talus" 

	1 - Click on "Sélectionner les lignes d'encadrement  du  talus"  and 
	select by clicking  on  the top and bottom lines of the slope in the
	drawing.

	2 - In  "Caractéristiques géométrique  de  la  barbule" = "Geometric
	characteristics  of  the  bank", set  "Distance curviligne entre les 
	lignes de liaisons" which  is  "the distance between the curvilinear
	connecting lines"  must be a decimal number or positive integer. The
	"Nombre d'espace entre les  lignes  de  pente  par  motif" = "Number 
	of  space  between  the  slope  lines"  should  be  an  integer. The 
	"Longueur  des  lignes  de  pentes"  =  "Length of  the slope lines"
	should also be a decimal number or an integer. 

	3 - Select "Bloc"  or  "lignes" to obtain the bank in blocks or not.
	If "Bloc" is selected, the block take the name you had set.

	4 - Click on "Tracer la barbule" = "Draw the bank" to automatically
 	draw the bank.

Notes: Several banks can be placed in the same block but a single insertion
of this block will be  realized.  The high and low lines of the slopes must 
be a single element of the drawing such as a line, a polyline, a spline.
