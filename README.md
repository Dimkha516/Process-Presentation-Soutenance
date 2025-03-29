# Process-Presentation-Soutenance
CECI EST UNE PETITE DOCUMENTATION PERSONNELLE POUR LA PRESENTION DU PROJET OFMS-CAMPAGNE

------------------------------------BACKEND--------------------------------------
-----------GESTION RECOMPENSES TRANSACTIONS
1) Configuration Connexion Base de données et service Mailing => .ENV; Config  
2) RECUPERATION DES TRANSACTIONS DU JOUR NON ENCORE RECOMPENSEES DANS LA BD MYSQL => Transaction/Repository-Service-Controller
3) RECUPERATION DES CAMPAGNES DU JOUR EN COURS DANS LA BD MONGO => Campagne/Service-Controller
4) RECHERCHE CORREPONDANCE CAMPAGNE-TRANSACTION POUR GROUPAGE => RewardService
5) SERVICE POUR LA NOTIFICATION AUX CLIENTS RECOMPENSES => App/Mail/RewardNotification
6) EXECUTION DES RECOMPENSES ET MIS A JOUR DES TRANSACTIONS CONCERNEES => App/Job/ProcessRewardJob

------------------------------------FRONTEND--------------------------------------
------------SIMULATION TRANSACTIONS CLIENTS POUR EFFECTUER RECOMPENSES;
