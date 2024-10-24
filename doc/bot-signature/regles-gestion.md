# Règles de gestion
# Configuration du bot
- R.G 1: Le système peut être arrêté, démarré ou en pause.
- R.G 2: L'état de pause peut être associé à une ou plusieurs promos.
- R.G 3: Le bot peut créer les messages à la demande.
# Rappeler à un formateur qu'il a oublié de faire signer
- R.G 4: Le message est lié à un channel de promo.
- R.G 5: Le message prend la forme d'un vote.
- R.G 6: Un apprenant de la promo peut lancer un vote pour rappeler au formateur qu'il a oublié de faire signer.
- R.G 7: Il y a un une liste selectionable contenant les formateurs liés a la promo.
- R.G 8: Un seul formateur peut être sélectionné à la fois.
- R.G 9: Il faut qu'un formateur soit sélectionner pour lancer le vote.
- R.G 10: Il faut trois votes pour que le vote soit un succès.
- R.G 11: Dès que le vote est un succès, le bot envoie un message privé au formateur pour l'avertir qu'il doit autoriser les apprenants à signer.
# Prévenir les apprenants qu'ils peuvent signer
- R.G 12: Le message est lié à un channel de promo.
- R.G 13: Le message permet de notifier les apprenants qu'ils peuvent signer.
- R.G 14: Seul les formateurs peuvent peuvent utiliser cette fonction.
- R.G 15: Le message est envoyé directement dans le fil de discussion signature.
- R.G 16: La promo est notifiée via un tag @.
- R.G 17: Le bot sauvegarde l'ID du message.
- R.G 18: Le message n'est utile que pendant que la signature est possible sur les plateformes externes.
- R.G 19: Le bot supprime le message quand il n'est plus utile.
# Rappeler à un apprenant qu'il a oublié de signer
- R.G 20: Le message est lié à un channel de promo.
- R.G 21: Le message contient la liste des apprenants liés a la promo.
- R.G 22: Seuls les formateurs peuvent interagir avec le message.
- R.G 23: Les formateurs peuvent selectionner un ou plusieurs apprenants.
- R.G 24: Il faut au moins un apprenant sélectionné pour valider le rappel.
- R.G 25: Les apprenants sélectionnés sont notifiés par message privé.
# Journalisation
- R.G 26: Le bot enregistre chaque fois qu'un utilisateur fait appel à lui dans un journal.
- R.G 27: Le journal écrit les informations de la manière suivante: date, émetteur, action, destinataire.
# Structuration de l'organisation
- R.G 28: Un formateur est lié à une ou plusieurs promotions.
- R.G 29: Une promotion est liée à un ou plusieurs formateurs.
- R.G 30: Un apprenant suit une formation à la fois.
- R.G 31: Une promotion regroupe plusieurs apprenants.
- R.G 32: Un apprenant appartient à une promotion.
- R.G 33: Une promotion a un chargé de projets.
- R.G 34: Un chargé de projets a une ou plusieurs promotions.
- R.G 35: Une formation peut être dispensée dans un ou plusieurs centres.
- R.G 36: Un centre peut proposer une ou plusieurs formations.
# Données nécessaires au bot
- R.G 37: Le bot a accès à la liste des formateurs.
- R.G 38: Le bot a accès à la liste des formations.
- R.G 39: Le bot a accès à la liste des promotions.
- R.G 40: Le bot a accès à la liste des apprenants.
- R.G 41: Le bot a accès à la liste des chargés de projets.
- R.G 42: Le bot a accès à l'ID Discord des utilisateurs.
- R.G 43: Le bot a accès à l'ID des canaux Discord des promotions.
- R.G 44: Le bot a accès à l'ID des fils Discord de signature.