# Spécifications fonctionnelles/ exigences fonctionnelles et non fonctionnelles

Une exigence fonctionnelle est un énoncé lié à la fonction principale ou au comportement attendu du système. Pour rédiger ces exigences, nous avons adopté un style concis, utilisant des phrases courtes qui expriment clairement une ou plusieurs fonctionnalités. Afin d’assurer une cohérence dans notre travail, nous avons appliqué un formalisme précis :  

**<objet> doit <verbe à l’infinitif> <fonctionnalité>.**  

En complément, les **exigences non fonctionnelles**, bien que rédigées dans un format similaire, portent sur des aspects différents. Elles ne décrivent pas directement une fonctionnalité, mais plutôt la manière dont cette fonctionnalité doit se comporter. Ces exigences se concentrent sur des critères tels que :  
- **Sécurité** : Assurer la protection des données et des utilisateurs.  
- **Performance** : Garantir des temps de réponse et une efficacité optimale.  
- **Ergonomie** : Rendre l’interface simple, intuitive et agréable à utiliser.  
- **Disponibilité** : Maintenir le système opérationnel à tout moment.  

Ces énoncés servent de base à toutes les étapes ultérieures du projet, en guidant la conception, le développement et les tests.  

## Exigences fonctionnelles

- Le bot doit permettre à un admin, un CDP et un directeur de gérer une promo, ce qui permet de créer, modifier ou supprimer une promo.
- Le bot doit permettre à un admin, un CDP et un directeur de gérer une formation, ce qui permet de créer, modifier ou supprimer une formation.
- Le bot doit permettre à un admin, un CDP et un directeur de gérer une fabrique, ce qui permet de créer, modifier ou supprimer une fabrique.
- Le bot doit permettre à un admin, un CDP et un directeur de gérer un channel, ce qui permet de créer, modifier ou supprimer un channel.
- Le bot doit permettre à un admin, un CDP et un directeur de gérer un channel, ce qui permet de créer, modifier ou supprimer un forum.
- Le bot doit permettre à un admin, un CDP et un directeur de gérer un channel, ce qui permet de créer, modifier ou supprimer un post.
- Le bot doit permettre à un admin , un CDP et un directeur de paramétrer et pré-enregistrer un channel.
- Le bot doit permettre à un admin , un CDP et un directeur de paramétrer et pré-enregistrer un post.
- Le bot doit permettre à un admin, un CDP et un directeur de sélectionner un channel dans une liste déroulante des channels pré-enregistrés.
- Le bot doit permettre à un admin, un CDP et un directeur de sélectionner un post dans une liste déroulante des posts pré-enregistrés.
- Le bot doit permettre de créer un channel vocal temporaire.
- Le bot doit permettre aux nouveaux arrivants ayant accepté le règlement de s'identifier.
- Le bot doit permettre aux admins, un CDP et un directeur d'accepter ou refuser les demandes d'identifications.
- Le bot doit permettre aux apprenants de savoir si leur demande d'identification a été acceptée.
- Le bot doit permettre à l'admin, un CDP et un directeur de masquer ou non les promos pour lui.
- Le bot doit permettre aux nouveaux arrivants d'avoir accès aux diffèrents channels.
- Le bot doit permettre l'archivage d'une promotion au bout de 1 mois après la fin de la session.

## Exigences non fonctionnelles

### Sécurité

- En accord avec le principe de moindre privilège, les fonctionnalités sensibles doivent être limitées aux admins et protégés par un système d'authentification robuste.
- En accord avec la RGPD, les données des nouveaux arrivants doivent être stockées de manière sécurisée.
- En accord avec la RGPD, les données des nouveaux arrivants doivent être protégées.
- En accord avec la RGPD, les nouveaux arrivants doivent accepter le traitement de leurs données.
- Les nouveaux arrivants ne doivent pas avoir accès aux channels avant d'avoir son identification accepté et d'avoir accepté le règlement.
- Le système doit permettre la journalisation des évènements survenus au sein de ce dernier.
- Les nouveaux arrivants doivent également être sensibilisés aux bonnes pratiques en termes de sécurité via un guide d'utilisation.
- Le Staff de Simplon doit être sensibilisés aux exigences de modération que requièrent les forums communs.

### Performance

- Le bot doit être réactif et répondre rapidement  aux commandes des utilisateurs et gérer plusieurs requêtes en même temps.

### Ergonomie

- Le bot doit offrir une interface ergonomique. 
- Le bot doit offrir des messages d'erreurs clair.

### Disponibilité

- Le bot doit être disponible en permanence, sauf pendant les périodes de maintenance, qui devraient de préférence avoir lieu le soir.

