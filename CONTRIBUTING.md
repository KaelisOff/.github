# Contribuer

Les *issues* et les *pull requests* sont bienvenues, en français ou en anglais.

## Avant de commencer

- Pour un changement important, ouvrez d'abord une *issue* pour en parler : ça évite de travailler
  pour rien.
- Une faille de sécurité ne se signale pas en *issue* : voir [SECURITY.md](SECURITY.md).

## Une pull request

- Une pull request = un sujet.
- Les tests passent (`go test -race ./...`), le code est formaté (`gofmt`) et `go vet` ne dit rien.
- Ajoutez un test pour ce que vous corrigez ou ajoutez.
- Messages de commit courts, en anglais, de préférence au format `type: description`
  (`fix: …`, `feat: …`, `docs: …`).
- Le code reste simple et sans dépendance de plus, sauf bonne raison.

## Écrire un agent

Pas besoin de passer par nous : partez du modèle
[agent-template-go](https://github.com/KaelisOff/agent-template-go) et publiez-le dans votre propre
dépôt. Le magasin d'agents, quand il ouvrira, les recompilera depuis leurs sources.

## Licence

En contribuant, vous acceptez que votre contribution soit publiée sous la licence du dépôt.
