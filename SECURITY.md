# Signaler une faille de sécurité

Merci de prendre le temps de le faire. Ne publiez pas la faille dans une *issue*, une *pull request*
ou ailleurs avant qu'elle soit corrigée.

## Comment

Ouvrez un **signalement privé** depuis l'onglet *Security* du dépôt concerné : *Report a
vulnerability*. Seuls les mainteneurs le voient.

Pour une faille de la box elle-même (son système n'est pas public), faites le signalement depuis
[agent-sdk-go](https://github.com/KaelisOff/agent-sdk-go/security/advisories/new).

Indiquez si possible :

- ce qui est touché (dépôt, version, ou version de la box) ;
- comment reproduire, même grossièrement ;
- ce qu'un attaquant pourrait en faire.

## Ce qui nous intéresse en particulier

- un agent qui sort de sa cage : réseau, fichiers de la box, autres agents, élévation de privilèges ;
- un agent qui obtient une capacité que le propriétaire n'a pas acceptée, ou qui contourne un
  garde-fou (limites, quotas, horaires) ;
- un paquet `.kagent` qui fait autre chose que ce que dit son manifeste ;
- une donnée de la box (conversations, documents, comptes) qui pourrait en sortir.

## Ensuite

Nous accusons réception sous quelques jours, puis nous vous tenons au courant de la correction. Si vous
le souhaitez, vous serez cité une fois la correction publiée.
