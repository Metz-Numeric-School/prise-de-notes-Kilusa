- ESN = Entreprise de service numerique
- Gestion de parc: 
	- Gestions de serveurs
	- gérer les mises a jours (parFeu, switch, ordinateur, etc..)
- Listes de tache a faire dans une entreprise en gestion de parc infromatique:
	- - Quels sont celle a faire tous les jours
		-  tout les semaines
		- tout les mois
		- tout les ans
- Autre liste savoir être, comment me comporter, comment se comporter face aux utilisateurs:
- -Faire deux VM plus tard:
- mettre en place un outil pour gerer un parc informatique
	- - Mettre en place un glpi sous linux:
		- Deux forums:
			- -it-connect
			- neptun
Si = System infromation
Contrat de maintenance = prestatire avec qui tu travaille

Nom des delais:
	gtr: TEMPS DE RETABLISSMENT (Obliger que ca marche)
	gti: Temps d'intervention (Pas obliger que ca marche ne garanti rien)
System information: = Information ciruculant dans l'entreprise
Gestion de parc informatique respecter, les bonnes pratique:
	- ITLI
	- Formation chez itili si on souhaite
- Glpi:
	- Gerer tous le parc informatique
	- Commencer avec l'inventaire
		- Ocsinvotory
	- Genere un ticket
		- créer plusieurs catégorie de tickets
			- Exemple:
				- Ticket pour le service IT
				- Ticket pour le service Compta
				- Etc...
- Pour changer l'adresse ip en ligne de commande sous linux:
	- - Fichier ou est stocker les informations de l'interface reseau
		- /etc/newtork/interfaces
	- Pour modifier l'adresse IP en static:
		- - iface eth0 inet static
		- - adresse IPv4: 192.168.16.10
		- netmask: 255.255.255.0
		- gateway: 192.168.16.1
		- dns -name servers: 8.8.8.8 4.4.4.4
	- Et modifier le dns:
		- Dans le /etc/reslov.conf
		- name server 192.168.16.1
	- Norme afnor norma francaise pour la maintenance:
		- 5 Niveaux de maintenance:
			- niveau1: Action simple
			- Niveau2: Opération mineur
			- Niveau3:  Opération avec diagnostics
			- Niveau4: Travaux maintenance de maintenance
			- Niveau5: Travaux de rénovation et de réparation
Reaseau NAT:
	- Transalation d'adresse
	- 
	- Types de maintenance:
			- Maintennce corrective
				- a eu lieux
				- Réparation
				- Dépannage
			- Maintenance preventiv:
				- N'a pas eu lieux
				- Tout fonctionne bien
				- Outils pour Anticiper la panne:
					- outils de supervision
				- Preventive systématique
				- preventive conditionnelle
			- Maintenance préventive systématique:
				- C'est moi qui definit la date
			- Maintenance préventive conditionnelle:
				- C'est 'si' il y a quelque chose qui se passe
		sauvegarde '321':
			- 3 sauvegarde 
			- sur 2 support differents 
			- 2 sauvegarde en site en (reseau)
			- 1 sauvegarde en externe (hors réseau)
	- Jamais:
		- redemarrer ou arreter un serveur en production
	- PCA:
		- plan de continuité de l'activité
	- PCI:
		- plan de continuité de l'informatique
Analyse multicritique:
	- R: Risque
	- I: Importance machine
	- C: Charge Machine
-Facteur Machine:
	Calculer facteur de machine en fonction de son évalutation:
		FACTEURmachine = R x I x C 
		Facteur machine elever:
				- Maintenance conditionnelle
		- Facteur Machine Ordinaires:
				- Maintenance préventive
		- Facteur machine banale:
				- Maitenance curentive
TCO:
	-Le temps d'occupation est un coup sur un system.
Serveur cluster:
	- Signifie:
		- Fonctionne tous ensemble
		- fait tous ensmeble
Diagramme d'ishiwaka:
	- 5m:
		- Metgode
		- Machinery
		- Management
		- Matériels
		- Manpower
QQOQCCP:
	  - Qui
	  - Quoi
	  - ou
	  - Quand
	  - Comment 
	  - Combiens
	  - Pourquoi
Pareto:
	- Diagramme 80/20:
-Roue de deming (PDCA):
		- Objectif de faire monter la roue:
			- Plan
			- Do
			- Action
			- Check
		- Amelioration continue
- Service qse:
	- Qualité service environnemental