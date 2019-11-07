Bienvenue dans le projet DACHM et merci d'avoir ouvert ce fichier! :-)

Ce fichier a pour but d'apporter des éclaicissement sur le sens des variables utilisés dans le PROJET APPEL DACHM ou de donner leur signification. il permettra aussi entre autre de présenter les structures définies. Bonne lecture!



******************     les structures    *************   
-la structure datnaiss 
	datnais= date de naissance de l'abonne
        jj= jour de naissance de l'abonne
        mm= mois de naissance de l'abonne
        aa= annee de naissance de l'abonne


-la structure abonne
      abonne(type)
      ab (variable)= abonne
      nomab= nom de l'abonne
      prenoab= prenom de l'abonne
      lieuab= adresse de l'abonne
      natab= nationalite de l'abonne
      dtnsab= date de naissance de l'abonne
      numab= numero de l'abonne
      cinab= numero CIN (carte d'identite nationale) de l'abonne
      credab=credit de l'abonne
      identification= variable entiere qui fonctionne comme un booleen
          =1 si l'abonne est identifie
          =0 si l'abonne n'est pas encore identifie


-la structure operateur
      operateur (type)
      op (variable)
      nomop= nom de l'operateur
      stoknum= les 100 numeros d'un operateur
      index= le nombre total d'index de chaque operateur (dans notre cas c'est 5)
      capitop= capital d'un operateur
      nbrindex= le nombre d'in dex de l'operateur
      nbrab= nombre d'abonne d'un operateur
      prxab= prix d'abonnement a un operateur
      ventop= nombre de vente de sims de l'operateur
      credini= credit initial d'un operateur
      app1=cout d'appel vers le mm operateur
      app2=cout d'appel vers un autre operateur
      app3=cout d'appel vers l'international
      sms1=cout d'sms vers le mm operateur
      sms2=cout d'sms vers un autre operateur
      sms3=cout d'sms vers l'international
      abonne ab[10]= chaque operateur a au maximum 10 operateur


******************************************************










******************     les variables    *************

-operateur op[20]: creation d'un tableau d'operateur avec une taille approximative (20)

-int Nop= nombre d'operateur, ce sera la taille reel du tableau d'op, il s'incrémentera chaque fois qu'on ajoutera un operateur

-int choix: on utilisera choix pour recueillir le choix de l'utilisateur au niveau du menu

int i, j, cpt, k, a, l: ces variables seront utilisé comme des compteurs ou pour des boucles

char rep, oprech[30];
-rep est utilisé pour recuperer les reponses des questions oui/non du programme
-oprech est utilisé chaque fois pour y stocker le nom d'un operateur qu'on recherche

int cpt2, temp;
-temp est un tempon qu'on utilise pour la generation de numero!

long temlong;
-temlong sert de tempon de long pour recuperer des saisie de long pour ensuite les traiter

char temchar[30];
-temchar sert de tempon de caractère pour recuperer des saisie de chaines pour ensuite les traiter

int temint;
-temint sert de tempon d'entier pour recuperer des saisis de nombres pour ensuite les traiter

******************************************************
