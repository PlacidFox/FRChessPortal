# FRChessPortal
WebApp des tournois d'échecs en France

Ecrit en Python avec Flask

1/ Web Scrapping du site : http://www.echecs.asso.fr/ - Récupération des tournois avec Selenium & Beautiful Soup :
- Tournois à cadence lente : http://www.echecs.asso.fr/ListeTournois.aspx?Action=ANNONCE&Level=1
- Tournois en 61mn : http://www.echecs.asso.fr/ListeTournois.aspx?Action=ANNONCE&Level=2
- Tournois rapides : http://www.echecs.asso.fr/ListeTournois.aspx?Action=ANNONCE&Level=3
- Tournois blitz : http://www.echecs.asso.fr/ListeTournois.aspx?Action=ANNONCE&Level=4

2/ Sauvegarde des annonces de tournois en cours dans un fichier .JSON

3/ Comparaison avec la précédente MAJ du fichier :
- notification des nouveaux tournois 
- affichage des tournois passés ou supprimés

4/ Portail web (Flask)
- recherche dans la base des tournois annoncés
- MAJ de la base
- sélection et affichage de tournois "à faire"


