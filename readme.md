System de badge
===============

Tâches:
-------
1. Install et Paramétrer le projet
   1. Installer la base (utiliser sqlite)
   2. Installer maildev pour tester les emails

2. Créer les commentaires
   1. créer entity commentaires
   2. créer form 
   3. créer controller, view
   4. ajouter les constrainst 

3. Créer le système d'authentification
   1. créer entity User
   2. paramétrer security.yml
   3. créer controller view pour login et sign up
   4. créer fixture user 

4. Tester fonctionnellement (avec liip/functional-test-bundle)
   1. Test sans authentication
   2. Test ajouter un commentaires


5. Créer un BadgeBundle
   1. Créer entity : badge et badgeunlock
   2. Créer un manager pour gérer unlock des badge 
      * Vérifier si on a un badge 
      * Vérifier si l'utilisateur possède le badge 
      * Débloquer le badge pour l'utilisateur
      * Emettre un évenement pour notifier l'utilisateur
      

