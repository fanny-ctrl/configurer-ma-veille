# Configurer ma veille

Skill pour Claude qui compose avec un avocat sa veille juridique hebdomadaire, puis l'installe sous forme de tâche planifiée qui tourne seule chaque semaine.

## Ce qu'il fait

Claude vous interroge sur vos matières et sous-thèmes, vos clients types, vos abonnements, le rythme souhaité et la destination du compte rendu. Il vous propose ensuite cinq à quinze sources, choisies dans un catalogue de plus de cent sources classées en vingt et une matières : juridictions, autorités de régulation, administrations, presse et doctrine en accès libre. Les sources sous abonnement sont signalées comme lectures conseillées, sans être intégrées à la tâche.

Après validation, Claude lance un passage d'essai sur les sept derniers jours, ajuste la consigne selon vos remarques, puis crée la tâche planifiée « Veille juridique hebdomadaire ». Chaque compte rendu classe les nouveautés par importance pour vos clients, avec pour chacune la référence exacte, ce qui change, les clients concernés et l'action éventuelle, puis les échéances des trois prochains mois.

## Exemple de demande

- « Configure ma veille. »

## Prérequis

Le skill fonctionne au mieux dans Cowork, qui permet de créer des tâches planifiées. Ailleurs, il vous remet la consigne dans un fichier et vous explique comment créer la tâche. Le connecteur Légifrance, s'il est activé, fiabilise les références ; il n'est pas obligatoire.

## Installation

**Dans l'application Claude (web, ordinateur, Cowork).** Téléchargez `configurer-ma-veille.zip` dans la rubrique [Releases](../../releases) de ce dépôt, puis ouvrez Paramètres → Capacités → Compétences et importez le fichier. Les compétences doivent être activées pour votre compte ; sur une offre Team ou Enterprise, un administrateur peut avoir à les autoriser.

**Dans Claude Code.** Copiez le dossier `configurer-ma-veille` dans `~/.claude/skills/`.

## Bon usage

La veille ne traite que des sources publiques : la tâche n'accède à aucune messagerie ni à aucun dossier du cabinet. Une veille automatisée peut mal résumer un texte ou manquer une nouveauté. Ouvrez chaque référence à sa source avant de la citer à un client : la veille outillée complète votre lecture, elle ne la remplace pas.

Pour proposer une source à ajouter au catalogue, ouvrez un signalement dans la rubrique [Issues](../../issues).

## Licence

Distribué sous la [licence publique de l'Union européenne (EUPL) v1.2](LICENSE). Vous pouvez l'utiliser, l'adapter et le redistribuer ; toute version modifiée et redistribuée doit rester sous EUPL ou sous une licence compatible. La version française de l'EUPL, qui fait également foi, est disponible sur le [site de la Commission européenne](https://interoperable-europe.ec.europa.eu/collection/eupl/eupl-text-eupl-12).

Fourni tel quel, sans garantie, dans les limites prévues par la licence.

Copyright © 2026 Fanny Adoue, avocate au barreau de Paris.
