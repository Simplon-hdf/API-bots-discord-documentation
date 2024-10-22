# Règles de gestion

Les règles de gestion d'un bot ont pour but de rassembler l'ensemble de ses fonctionnalités et les règles qui y sont associées. Vous trouverez donc ci-dessous les règles de gestions du bot onboarding.

## Gestion de promotion
- **RG1** : Une promotion contient un nom qui la décrit 
- **RG2** : Une promotion contient une date de début et une date de fin
- **RG3** : Seuls un administrateur et un directeur peuvent créer une promotion
- **RG4** : Seuls un administrateur et un directeur peuvent modifier une promotion 
- **RG5** : Seuls un administrateur et un directeur peuvent supprimer une promotion 
- **RG6** : Lors de la modification, un message pour confirmer apparait
- **RG7** : Lors de la suppression, un message pour confirmer apparait
- **RG8** : Lors de la création, un message pour confirmer apparait
- **RG9** : Pour créer une promotion il sera nécesssaire de sélectionner sa formation et sa fabrique associé
- **RG10** : La création d'une promotion crée également un rôle associé avec le nom de la promo
- **RG11** : La promotion disparaît un mois après la fin de la session associée
- **RG12** : Une promotion est forcément lié à une fabrique
- **RG13** : Une promotion est forcément lié à une promotion
- **RG14** : Les promotions seront triées visuellement par fabrique

## Gestion de formation
- **RG15** : Une formation contient un nom qui l'a décrit
- **RG16** : Une formation contient un nom qui la décrit 
- **RG17** : Seuls un administrateur et un directeur peuvent créer une formation
- **RG18** : Seuls un administrateur et un directeur peuvent modifier une formation 
- **RG19** : Seuls un administrateur et un directeur peuvent supprimer une formation 
- **RG20** : Lors de la modification, un message pour confirmer apparait
- **RG21** : Lors de la suppression, un message pour confirmer apparait
- **RG22** : Lors de la création, un message pour confirmer apparait
- **RG23** : Lors de la création d'une formation, il sera possible de sélectionner des canaux déjà pré-enregistré
- **RG24** : Lors de la modification d'une formation, il sera possible de sélectionner des canaux déjà pré-enregistré
- **RG25** : Une formation contient un template de channels organisé qui lui est dédié

## Gestion de fabrique
- **RG26** : Une fabrique contient un nom qui la décrit 
- **RG27** : Seuls un administrateur et un directeur peuvent créer une fabrique
- **RG28** : Seuls un administrateur et un directeur peuvent modifier une fabrique
- **RG29** : Seuls un administrateur et un directeur peuvent supprimer une fabrique
- **RG30** : Lors de la modification, un message pour confirmer apparait
- **RG31** : Lors de la suppression, un message pour confirmer apparait
- **RG32** : Lors de la création, un message pour confirmer apparait
- **RG33** : Une fabrique est lié à tous les apprenants en cours de formation dans celle-ci
- **RG34** : Une fabrique n'est plus lié à un apprenant lorsqu'il termine sa formation
- **RG35** : Une création de fabrique a pour conséquence la création de son rôle discord associé
- **RG36** : Seuls un administrateur et un directeur peuvent notifier les personnes concerné par une fabrique 

## Gestion des channels
- **RG37** : Seuls un administrateur et un directeur peuvent créer un channel dans le stock de channel
- **RG38** : Seuls un administrateur et un directeur peuvent modifier un channel dans le stock de channel
- **RG39** : Seuls un administrateur et un directeur peuvent supprimer un channel dans le stock de channel
- **RG40** : Un channel contient un nom unique qui le décrit 
- **RG41** : Un channel a un emoji qui le défini
- **RG42** : Deux channels peuvent avoir le même emoji
- **RG43** : Lors de la création d'un channel, celui-ci peut être stocké en tant que template de channel
- **RG44** : Un template de channels générique est disponible
- **RG45** : Les channels disparaissent un mois après la fin de la session associé
- **RG46** : Une template de channels est une liste de channels organisés
- **RG47** : Les channels disparaissent un mois après la fin de la session associé

## Gestion des channels vocaux
- **RG48** : Les channels vocaux peuvent être temporaire

## Gestion des Forums
- **RG49** : Un forum contient un nom unique qui le décrit
- **RG50** : Un forum peut être privé
- **RG51** : Dans le cas d'un forum privé, l'administrateur choisir les membres ou rôles qui peuvent rejoindre ce forum
- **RG52** : Seuls un administrateur et un directeur peuvent créer un forum
- **RG53** : Seuls un administrateur et un directeur peuvent modifier un forum
- **RG54** : Seuls un administrateur et un directeur peuvent supprimer un forum
- **RG55** : Un forum peut contenir une guideline indiquant la nature de ce forum
- **RG56** : Un forum peut contenir des tags qui lui sont propres pour filtrer les posts

## Gestion des Posts
- **RG57** : Empêcher les apprenants de créer des posts
- **RG58** : Un post contient un titre
- **RG59** : Un post contient un message
- **RG60** : Un post peut contenir un emoji
- **RG61** : Un post peut contenir une image
- **RG62** : Un post peut contenir une réaction par défaut
- **RG63** : Un post peut contenir un ou plusieurs tags
- **RG64** : Seuls un administrateur et un directeur peuvent créer un post dans le stock de post
- **RG65** : Lors de la création d'un post, celui-ci peut être stocké en tant que template de post
- **RG66** :  Un template de posts générique est disponible
- **RG67** : Seuls un administrateur et un directeur peuvent modifier un post dans le stock de post
- **RG68** : Seuls un administrateur et un directeur peuvent supprimer un post dans le stock de post


## Gestion d'identification
- **RG69** : Une demande d'identification est effectuée par un nouvel arrivant
- **RG70** : Une demande d'identification passe par un formulaire
- **RG71** : Un formulaire de demande d'identification contient le nom de la personne
- **RG72** : Un formulaire de demande d'identification contient le prénom de la personne
- **RG73** : Un formulaire de demande d'identification contient l'username discord de la personne
- **RG74** : Un formulaire de demande d'identification contient l'adresse email de la personne
- **RG75** : Un formulaire de demande d'identification contient des informations supplémentaires de la personne
- **RG76** : Seul un administrateur, un CDP, un membre du staff peut accepter/refuser une demande d'identification
- **RG77** : La personne acceptant la demande d'identification peut attribuer le rôle de staff ou apprenant
- **RG78** : Lorsque ce rôle est apprenant, la personne acceptant la demande d'identification lui attribue le rôle de sa formation
- **RG79** : Une fois un rôle attribué au nouvel arrivant, ce rôle de nouvel arrivant lui est retiré
- **RG80** : Une fois le processus d'identification terminé, la demande d'identification est supprimée