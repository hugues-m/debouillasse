---
name: debouillasse
description: "Débouillassifier la prose française sans altérer le fond. À utiliser pour rédiger, traduire vers le français, réviser ou auditer un texte destiné à des humains lorsque la voix paraît artificielle, vague, gonflée ou trop formatée."
---

# Dé-bouillassification

Rendre chaque phrase nécessaire, précise et naturelle en français, sans altérer ce que l'auteur affirme.

## Contrat de fidélité

Préserver :

- les faits, chiffres, dates, unités, comparaisons, chronologie et attributions ;
- les acteurs, objets et relations auxquels chaque affirmation se rapporte ;
- la causalité, la négation, les conditions, les exceptions et la portée ;
- le degré de certitude, d'obligation, d'importance et d'intensité ;
- la position de l'auteur, y compris ses hésitations et ses jugements ;
- le lectorat, le registre, la variété de français et les choix entre `tu` et `vous`, `on` et `nous` ;
- les termes techniques, juridiques, scientifiques ou institutionnels exacts ;
- la structure utile, les citations, liens, commandes, identifiants et passages déclarés immuables.

La précision prime sur l'élégance. Un signal n'est jamais une faute à lui seul. Une réécriture peut ne rien changer lorsque le texte remplit déjà sa fonction.

Une voix naturelle vient de choix précis. Elle ne vient pas de fautes volontaires, d'argot ajouté, d'anecdotes inventées, d'une opinion forcée ou d'une irrégularité artificielle.

## Méthode

1. **Cadrer.** Déterminer le mode demandé, le lectorat, le support, le registre, la variété de français, la voix à préserver et les passages immuables. En l'absence d'indication, les déduire du texte sans interrompre le travail. Le cadrage est achevé lorsque chaque contrainte de fidélité est connue.
2. **Cartographier.** Inventorier chaque proposition du texte, puis relever la fonction de chaque paragraphe : informer, expliquer, démontrer, nuancer, instruire, convaincre ou faire entendre une voix. Distinguer l'information substantielle du cadrage, de la répétition et de l'étiquette décorative. La cartographie couvre chaque proposition substantielle ; chaque paragraphe possède une fonction identifiable ou peut disparaître sans perte.
3. **Diagnostiquer.** Lire [la grille des signaux](references/signaux.md), puis examiner chaque paragraphe. Retenir un problème seulement si la formulation est vide, imprécise, injustifiée, répétitive, illogique, peu idiomatique ou inadaptée au registre. Le diagnostic est complet lorsque chaque signal relevé possède soit un défaut précis, soit une raison de rester.
4. **Réécrire.** Corriger dans cet ordre : contenu, raisonnement, structure, syntaxe, vocabulaire, rythme, typographie. Faire la plus petite modification suffisante. Employer uniquement les informations présentes dans le texte ou autorisées par la demande. La réécriture s'arrête lorsque chaque problème est corrigé ou conservé pour une raison de fidélité identifiable.
5. **Contrôler.** Comparer le résultat au texte initial, paragraphe par paragraphe. Le contrôle passe lorsque le contrat de fidélité tient, que chaque phrase restante remplit une fonction et que le résultat respecte le mode de sortie.

## Modes de sortie

- **Rédaction, traduction ou révision.** Rendre directement le texte propre, sans commentaire ni préambule, sauf demande contraire.
- **Audit ou détection.** Conserver le texte. Donner pour chaque problème le passage concerné, le défaut précis et une correction proposée. Ne signaler aucune simple occurrence de catalogue.
- **Demande mixte.** Donner d'abord le texte propre, puis les explications explicitement demandées.

## Critères de sortie

Le texte est prêt lorsque :

- chaque phrase apporte une information, une relation logique, une instruction, un exemple ou un effet de voix voulu ;
- aucun fait, chiffre, exemple, témoignage, mécanisme, source ou jugement n'a été inventé ;
- les attributions, degrés de certitude, obligations, négations, conditions et exceptions sont intacts ;
- chaque acteur, objet et relation substantielle du texte source demeure identifiable ;
- chaque jugement d'importance est étayé, attribué ou retiré sans perte de sens ;
- chaque connecteur exprime une relation réelle et chaque pronom possède un référent clair ;
- les termes précis restent stables et le nombre de parties vient du contenu ;
- la voix, le registre, la variété de français et la typographie du projet restent cohérents ;
- chaque signal conservé a une fonction identifiable.

Un score de détection automatisée n'est jamais un critère de réussite.
