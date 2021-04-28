# exo-dlt
Answering Blockchain Related Questions

#Un arbre de merkle nécessite une paire de hashes pour produire un nouveau hash parent. Il faut donc a absolument que le nombre de transactions qui produiront le Merkle root soit #pair.
#Comment est géré le cas ou le nombre de transactions dans le Block à valider est impair pour générer un Merlke root ?

 Dans le cas où le nombre d'empreintes à combiner est impair, on combine la dernière empreinte avec elle-même. 

#Dans le réseau bitcoin, Comment un nouveau noeud arrive t'il à retrouver ses pairs et ainsi rejoindre le réseau ? Expliquer le processus avec vos propres mots.

C'est comme si une personne rentrait dans un labyrinthe géant et il avait dans sa poche une carte géante avec tout l'historique des chemins emprunter par les gens qui ont déjà un lien vers la sortie du labyrithe, comme le merkel root est aussi dans chaque transaction, il faut remonter les hashes, et les valider un par un, en les comparent, jusqu'à la maison mère. 


#Pouvez vous nommer au moins une personne qui a ou aurait pu influencer directement ou indirectement la création de Bitcoin par ses travaux (une personne qui n'a pas été nommée dans le cours)?

https://en.wikipedia.org/wiki/Wei_Dai

#Avec vos propres recherches et grâce aux compétences acquises en cours pouvez vous expliquer comment une Blockchain crée un lien entre ses différents Blocks?

Avec des hashes, avec le merkel root, avec des id, avec des adresses. Et tout cela est lié, comme une sorte d'array géant, avec lequel on peut seulement .push()

Jamais .pop()

#Quelle structure de données informatique peut représenter le mieux cette chaine de Block: https://en.wikipedia.org/wiki/List_of_data_structures ?

Un Arbre

#Si je souhaite modifier une transaction de 10 bitcoin que j'ai effectué il y a 6 mois en une transaction de 1 Bitcoin, que dois je modifier dans la Blockchain et que dois je mettre en oeuvre pour que cette modification persiste ?
Est ce possible selon vous ?

Il faudrait contrôler plus de 51% du réseaux et être majoritaire dans l'information qui circule, cela pourrait réussir, si même les développeurs n'ont pas de timestamp alternatif ect de la transaction, des kill-switch, que sais-je. 

