# Résumé des commandes Git:

Lorsque tu crée un nouveau projet , tu dois initialiser le dépot Git avec la commande "git init"

Créer également un dépot sur github (New Repository)

Ensuite, choisir quels fichiers ajouter sur votre dépot. Pour cela, vous pouvez utiliser la commande "git add"

 * "git add NOM_DU_FICHIER" : ajoute uniquement un fichier choisi
 * "git add *" : pour ajouter tous les fichiers du répertoire courant.

Une fois les fichiers ajoutés, vous devez indiquer un message qui expliquera ce que vous avez fait. Pour cela, vous pouvez utiliser la command "git commit -m "MESSAGE""

Vous devez ensuite choisir sur quel branche vous allez travailler. Par défaut, vous devez traviller sur la branche 'main'. Pour choisir la branche main vous devez utiliser la commande:
 * "git branch -m main" <-- cette commande est a exécuter une seule fois, comme git init.

Vous devez églament indiquer à Git sur quel dépot distant vous souhaitez travailler avec la commande :
 * "git remote add origin URL_DU_DEPOT. <-- Cette commande est a exécuter une seule fois, comme git init et git branch -m main.

Pour finir, pour envoyer les modifications sur le dépot distant, vous devez utiliser les commandes suivantes en boucles :
 * "git add *
 * "git commit -m "MESSAGE" "
 * "git push"

INFO: Aprés le premier "git push -u origin main", vous pouvez utiliser seulement "git push"

## En résumé
### A la création d'un nouveau projet :
* selectionner le fichier avec cd <C:\Users\jolan\Desktop\Nouveau dossier github ou autre>
* git init 
* git add * 
* git commit -m "MESSAGE"
* git branch -m main
* git remote add origin URL_DU_DEPO
* git push -u origin main

### A chaque nouvelle modif: 
* git add *
* git commit -m "MESSAGE"
* git push

# Figma associé :
* " https://www.figma.com/design/8FGADlaiWDP7RnS9qrl1yN/Untitled?node-id=0-1&p=f&t=irHdhiUw864fjt6H-0 "