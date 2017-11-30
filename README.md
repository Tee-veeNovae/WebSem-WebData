# WebSem-WebData

Pour lancer Fuseki avec les 3 datasets : 
- Modifier le create.ttl pour faire pointer les paths vers les destinations correspondantes et le placer dans :  "path/to/Fuseki/run/configuration/create.ttl"
- Executer la commande suivante : ./path/to/Fuseki ./fuseki-server --update --config="path/to/Fuseki/run/configuration/create.ttl"
- Dans "path/to/Fuseki/run/configuration/" ajouter deux autres .ttl correspondant aux fichier de configs pour la création automatique des deux autres datasets
- Ceux-ci existe déjà ici sous les noms : "createOtherSet1.ttl" et "createOtherSet2.ttl", ne pas oublier de les modifier et de pointer vers les bon paths des deux .ttl et du .rules qui leurs correspond
