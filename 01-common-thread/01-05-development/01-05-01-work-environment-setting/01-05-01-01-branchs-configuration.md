# Mise en place du dépôt et des branches

Un dépôt commun a été créé entre les différentes équipes de travail. Le choix a été fait de mette en place le modèle de branches git-flow. Il s'agit d'un flux de travail où les branches sont découpées de la manière suivante:
- la branche main qui ne contient que les releases stables
- la branche develop qui fait le lien entre la branche main et les branches feature
- Les branches feature, chaque feature correspond à une fonctionnalité et est mergée avec develop lorsuq'elle est terminé.

Ajouté à ces branches principales:
- Les branches fix qui permettent de corriger une erreur de la branch develop
- Les branches hotfix qui corrigent les bug de la main

Pour une politique de commits homogène, nous nous somme accordé sur la mise en place de la convention de nommage Angular. Il s'agit d'une convention de nommage avec des règles stricte.
Chaque commit sera formaté de la manière suivante:
- un premier message nommé header sous la forme suivante: <type>(<scope>): <short summary>
    -> Le type désigne de type de commmit, celà peut être docs, fix, feature 
    -> le scope(optionnel) sera le dossier ou fichier concerné
    -> :(espace) seront systématiquement ajouté
    -> un message écrit au présent, pas de majuscule, pas de point à la fin
- Un second message nommé body (optionnel) indiquera des précisions liées à ce commit
- Enfin, un message de footer (aussi optionnel), peut comporter des informations sur un changment impoortant. C'est aussi ici que l'on ajoute la référence de l'issue gitHub ou du numéro de ticket Jira concerné

### quelques bonnes pratiques
git --force-with-lease est préféré à un git --force simple. \
git switch est également préféré à git checkout
dans notre cas pour démarrer est finish une feature, nous employons git flow feature start feature-name et git flow feature finish feature-name