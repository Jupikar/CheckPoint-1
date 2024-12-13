
# CheckPoint 1 

**1. Donne une ligne de commande bash qui permet de lister la liste des utilisateurs d'un système Linux :**
`cat /etc/passwd`

**2. Quelle commande bash permet de changer les droits du fichier myfile en rwxr—r-- ?**
`chmod 755 myfile`

**3. Comment faire pour que les fichiers pdf d'un dépôt local git ne soient pas pris en compte lors d'un git push ?**
Créer un fichier .gitignore dans le dépot et y ajouter les fichiers .pdf

**4. Quelles commandes git utiliser pour fusionner les branches main et test_valide ?**
Utiliser la commande `git merge test_valide` depuis la branche main

**5. Donne la(les) ligne(s) de commande(s) bash pour afficher le texte suivant :**

echo " Malgré le prix élevé de 100$, il a dit "Bonjour ! " au vendeur : "

echo " - "Bonjour est-ce que ce clavier fonctionne bien ? " "

echo " - "Evidemment ! On peut tout écrire avec, que ce soit des pipe '|' ou bien des backslash '\\' ! " " 

echo " - "Même des tildes '~' ? " "

echo " - "Evidemment ! " "

**6. La commande jobs -l donne le résultat ci-dessous :**
wilder@Ubuntu:~$ jobs -l
[1]  37970 En cours d'exécution   gedit &
[2]  37971 En cours d'exécution   xeyes &
[3]- 37972 En cours d'exécution   sleep
*Quelle commande te permet de mettre en avant le processus gedit ?*
Avec la commande `fg 1`

**7. Quels matériels réseaux sont sur la couche 2 et la couche 3 du modèle OSI ? Donne leurs spécificités.**
- Couche 2 (Liaison de données):
    - Switch: Transmettent les trames en fonction des adresses MAC.
- Couche 3 (Réseau):
    - Routeurs: Transmettent les paquets en fonction des adresses IP et acheminent les données entre les réseaux.

**8. Quels sont les équivalent PowerShell des commandes bash cd, cp, mkdir, ls.**
- cd: `Set-Location`
- cp: `Copy-Item`
- mkdir: `New-Item -ItemType directory`
- ls: `Get-ChildItem`

**9. Dans la trame ethernet, qu'est-ce que le payload ?**
Le payload d'une trame Ethernet est la partie de la trame qui contient les données réelles à transmettre

**10. Pourquoi les classes IP sont remplacées par le CIDR ?**
Le CIDR (Classless Inter-Domain Routing) a remplacé les classes IP pour plusieurs raisons :
- Flexibilité: Le CIDR permet une allocation plus flexible des adresses IP, en permettant des tailles de sous-réseaux variables.
- Optimisation: Il réduit le gaspillage d'adresses IP et facilite la gestion des réseaux.
- Évolutivité: Le CIDR s'adapte mieux aux réseaux de grande taille et aux besoins évolutifs des organisations.
