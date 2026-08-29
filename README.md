# À bas la bouillasse

[![Installations skills.sh](https://skills.sh/b/hugues-m/debouillasse)](https://skills.sh/hugues-m/debouillasse)

Personne n’a envie de lire votre bouillasse.

Débouillasse est une compétence d'agent consacrée à la dé-bouillassification du français. Elle repère la prose vague, gonflée ou trop bien rangée, puis la réécrit sans inventer de faits ni effacer la voix de l'auteur.

Elle sert à rédiger, traduire vers le français, réviser ou auditer un texte. Une source peut être écrite dans une autre langue, mais la compétence ne produit et ne révise que du français.

## Installation

Pour installer Débouillasse dans Codex, Claude Code et Cursor, pour tous vos projets (Node.js 22.20 au minimum) :

```bash
npx skills@latest add hugues-m/debouillasse \
  --skill debouillasse \
  --agent claude-code \
  --agent codex \
  --agent cursor \
  --global \
  --yes
```

Pour choisir interactivement les agents et la portée de l'installation :

```bash
npx skills@latest add hugues-m/debouillasse
```

Pour mettre à jour une installation globale :

```bash
npx skills@latest update --global debouillasse
```

Cette installation repose sur le [format ouvert Agent Skills](https://agentskills.io/specification) et l'[outil d'installation de Vercel Labs](https://github.com/vercel-labs/skills).

## Utilisation

Dans Codex :

```text
$debouillasse Réécris ce texte. Garde le tutoiement et le ton un peu sec.
```

Dans Claude Code ou Cursor :

```text
/debouillasse ce texte sans le réécrire. Relève uniquement tics de prose chelous.
```

La compétence peut aussi se déclencher automatiquement lorsqu'une demande porte sur la révision d'un texte français artificiel.

## Exemples

### Texte informatif pénible

Version bouillasse :

> À l'heure où le vivre-ensemble constitue plus que jamais un enjeu majeur, le comité des fêtes de Gneuleu-en-Porti vous invite à vivre une expérience gustative unique et fédératrice. Cette manifestation incontournable mettra la saucisse à l'honneur dans une ambiance authentique, conviviale et résolument festive, créant ainsi des moments de partage inoubliables pour petits et grands. Rendez-vous samedi 14 septembre, dès 11 h, sur la place de la Mairie. Au programme : concours de la plus longue saucisse, fanfare municipale et tombola dont le premier prix est un jambon de 8,4 kg.

Version débouillassée :

> Le comité des fêtes de Gneuleu-en-Porti organise sa fête à la saucisse samedi 14 septembre, dès 11 h, sur la place de la Mairie. Au programme : concours de la plus longue saucisse, fanfare municipale et tombola. Le premier prix est un jambon de 8,4 kg.

### Explication technique chiante

Avant :

> Il convient de noter que la mise en place du cache permet d'optimiser significativement les performances de l'application, garantissant ainsi une expérience plus fluide. Dans nos mesures, le temps de réponse médian est passé de 480 à 190 ms.

Après :

> Le cache a fait passer le temps de réponse médian de 480 à 190 ms dans nos mesures.

## Détection de contenu IA

Un détecteur peut illustrer l'effet de la dé-bouillassification.

Copyleaks a classé pour notre exemple (version bouillasse) de 820 mots à **100 % de texte IA**, contre **0 %** pour la version débouillassifiée de 386 mots.

[Voir le rapport, les captures et les deux textes](./exemples/minitel.md).

## Ce que la compétence protège

- Les faits, les chiffres, les attributions et le degré de certitude.
- Le registre, la variété de français et les termes exacts.
- Les guillemets français, les apostrophes typographiques et les autres choix de ponctuation lorsqu'ils sont justes.
- Les aspérités qui appartiennent réellement à l'auteur.

Débouillasse ne fabrique ni anecdotes, ni opinions, ni oralité pour « faire humain ». Elle préfère ne rien changer plutôt que de remplacer une bouillasse par une autre.

## Inspiration

Inspiré de la compétence [unslop de pstack](https://github.com/cursor/plugins/blob/main/pstack/skills/unslop/SKILL.md). Débouillasse en reprend l'intention, avec un diagnostic et des règles entièrement reconstruits pour le français.
