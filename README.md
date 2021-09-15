# Syteme Upload Medias
# Nom :
Uploder Medias
## Objectif :
uploader un media Objectif : les contributeur envoient un media ou des medias au site

## Acteurs principaux :
contributor
systeme 
Dates :
15/09/2021 date de but 
## Responsable :
mr samb.
## Version :
version Beta
La deuxième partie contient la description du fonctionnement du cas sous la forme d'une séquence de messages échangés entre les acteurs et le système. Elle contient toujours une séquence nominale qui décrit de déroulement normal du cas. À la séquence nominale s'ajoutent fréquemment des séquences alternatives (des embranchements dans la séquence nominale) et des séquences d'exceptions (qui interviennent quand une erreur se produit).

## Les préconditions :
contributor is registred 
page Contribotor => Upload 
## Des scénarii :
1. contirbuteur loggé
2. contributeur charge en lots ou une par une en drap en drop
3. le systeme valide la taille l'orientaione le poid la durée du media
	1. le systeme valide => stockage des medias
	2. le systeme refuse =>renvoie etape 2 
4. le contributeur rempli les champs du formulaire (mots clé =>voir systeme de mots clé,category titre etc) 
5. administrator valide les mots clé (a voir trop d'etape)
6. le systeme demande si photo de face 	
	 1. Oui demande d'autorisation droit a l'image
 	 	1. upload autorisation 
  		2. attente validation
  		3. soummission contrat de vente medias6.  non

	2. soummission contrat de vente medias 
7. validation de données du formulaire par systeme front
8. soumission du formulaire
9.  A verification formulaire coté back validation données 
	 1. ok => inscription en bd 
9. B false retour etape 7
10. soumission des données a l'admin


## Des postconditions :
elles décrivent l'état du système à l'issue des différents scénarii.
La troisième partie de la description d'un cas d'utilisation est une rubrique optionnelle. Elle contient généralement des spécifications non fonctionnelles (spécifications techniques…). Elle peut éventuellement contenir une description des besoins en termes d'interface graphique.
