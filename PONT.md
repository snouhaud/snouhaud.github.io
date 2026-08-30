# Le pont des mises à jour

`kodama/appcast.xml` et `kumoji/appcast.xml` ne servent pas ce site. Ce sont des copies
des flux de mises à jour, posées ici pour une seule raison : **les applications déjà
installées interrogent ces adresses**, gravées dans leur `Info.plist` au moment où elles
ont été construites.

    https://snouhaud.github.io/kodama/appcast.xml
    https://snouhaud.github.io/kumoji/appcast.xml

Tant que les dépôts `snouhaud/kodama` et `snouhaud/kumoji` publiaient leurs propres Pages,
ces deux chemins leur appartenaient et ces fichiers restaient masqués — un dépôt projet
l'emporte sur le dépôt utilisateur pour son sous-chemin. Depuis leur transfert vers
l'organisation *steveoctets*, plus personne ne réclame ces chemins : c'est ce dépôt qui
les sert, et le pont prend le relais sans interruption.

## Ce qu'il faut en faire

À **chaque publication**, tant que le pont existe : y recopier le flux, comme dans le dépôt
de l'application.

Le pont peut disparaître quand plus aucune copie n'interroge l'ancienne adresse — c'est-à-dire
quand toutes sont passées à une version dont le `SUFeedURL` pointe `steveoctets.github.io`.
Rien ne le signale ; dans le doute, le garder ne coûte que deux fichiers.
