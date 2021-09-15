# upload
 Description textuelle des cas d'utilisation

Le diagramme de cas d'utilisation décrit les grandes fonctions d'un système du point de vue des acteurs, mais n'expose pas de façon détaillée le dialogue entre les acteurs et les cas d'utilisation. Bien que de nombreux diagrammes d'UML permettent de décrire un cas, il est recommandé de rédiger une description textuelle, car c'est une forme souple qui convient dans bien des situations.

Une description textuelle couramment utilisée se compose de trois parties.

La première partie permet d'identifier le cas, elle doit contenir les informations qui suivent.

#Nom :
uploader un media
Objectif :
les contributeur envoient un media ou des medias au site 
##Acteurs principaux :
contributor
systeme 
Dates :
15/09/2021 date de but 
##Responsable :
mr samb.
##Version :
version Beta


##Les préconditions :
contributor is registred 
page Contribotor => Upload 
##Des scénarii :
1.contirbuteur loggé
2.contributeur charge en lots ou une par une en drap en drop
3.le systeme valide la taille l'orientaione le poid la durée du media
3.a le systeme valide => stockage des medias
3.b le systeme refuse =>renvoie etape 2 
4.le contributeur rempli les champs du formulaire (mots clé =>voir systeme de mots clé,category titre etc) 
5. administrator valide les mots clé (a voir trop d'etape)
6. le systeme demande si photo de face 
6.a oui demande d'autorisation droit a l'image
  =>upload autorisation 
  => attente validation
  => soummission contrat de vente medias
6.b non
=> soummission contrat de vente medias 
7.validation de données du formulaire par systeme front
8.soumission du formulaire
9.verification formulaire coté back validation données 
9.a ok => inscription en bd 
9.b false retour etape 7
10. soumission des données a l'admin
9

##Des postconditions :
elles décrivent l'état du système à l'issue des différents scénarii.
La troisième partie de la description d'un cas d'utilisation est une rubrique optionnelle. Elle contient généralement des spécifications non fonctionnelles (spécifications techniques…). Elle peut éventuellement contenir une description des besoins en termes d'interface graphique.
