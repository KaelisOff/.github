# Kaelis

**L'IA qui reste chez vous.**

Kaelis est une box d'IA locale, qu'on branche comme une box internet. Le modèle, les conversations,
les documents et les agents tournent **dans la boîte** : rien ne part dans le cloud, aucun compte en
ligne n'est nécessaire.

Elle est pensée pour ceux qui manipulent des informations confidentielles (avocats,
experts-comptables, cabinets…) et pour les foyers qui veulent une IA sans donner leurs données.

## Les agents

Sur la box, des **agents** travaillent pour vous : des automatisations qui tournent seules, avec le
modèle de la box. Ils sont **open source** et n'importe qui peut en écrire.

Un agent est traité comme du code non fiable : il tourne dans un conteneur **sans réseau**, sans accès
aux fichiers ni aux secrets, et n'agit qu'à travers des **capacités** de la box (le modèle, une
mémoire privée, des notifications, des demandes d'accord…). Le propriétaire voit chacune avant
d'installer, et c'est la box qui applique les garde-fous.

| Dépôt | |
|---|---|
| [agent-sdk-go](https://github.com/KaelisOff/agent-sdk-go) | le kit de développement en Go : protocole, box simulée pour les tests, paquets reproductibles |
| [agent-template-go](https://github.com/KaelisOff/agent-template-go) | un modèle prêt à l'emploi pour écrire son agent |
| [agent-prospection](https://github.com/KaelisOff/agent-prospection) | notre premier agent : trouver des clients par email, avec des garde-fous intouchables (en conception) |

## Où en est-on

Kaelis est en développement : un prototype tourne, il n'est pas encore en vente. Le système de la box
est propriétaire ; tout ce qui sert à écrire des agents est ici, sous licence libre.

## Sécurité

Une faille ? Merci de la signaler en privé, pas dans une *issue* : voir [SECURITY.md](https://github.com/KaelisOff/.github/blob/main/SECURITY.md).

---

**In English.** Kaelis is a local AI box: the model, conversations, documents and agents run inside
the box, nothing goes to the cloud. Agents are open-source automations that run sandboxed, without
network access, and act only through capabilities the owner approved. This organization hosts the
agent SDK, a template and our first agents.
