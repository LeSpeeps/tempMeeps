tags:: #pro/code, #Meeps 


### Update 1 - White Wave  (✅)
---
**Prémices**
- Réécriture de l'architecture (cogs).
- Ré-initialisation du serveur.
- Schéma de la base de données !
![ANG-2023-02-06_14-41](https://user-images.githubusercontent.com/110334321/217063878-fc356e56-472e-4e8d-be7c-c1935a45be9e.png)

*Fait le 05/06/2023*

<br />
<br />
<br />

### Update 2 - Moody Blues
---
<u>Collection des message et recensement des channels</u> <br />
Meeps doit être en mesure d'intégrer les messages du serveur entier dans la base de donnée qui sera en partie générée pour l'occasion (seule la **partie bleue** et la table ANG_USER vont être générées). <br />
<img width="537" alt="Pasted image 20230206193047" src="https://user-images.githubusercontent.com/110334321/217063614-0326f025-16e3-4e83-8ac3-6e4173af4408.png">

L'idée est de premièrement recenser les messages, beaucoup de fonctionnalités tournent autour de ces derniers, sans les avoir concrètement sur un serveur, c'est difficile de réaliser le reste.

<br />

#### Additionnel.
--
- Réimplémentation du iFart, cela nécessite d'étendre la base de données (partie rose).
- Réimplémentation du iputedemere, cela nécessite aussi d'étendre la base de données (partie rose).
- 


<br />
<br />
<br />

###   Update 3 - Gold experience
---
#### **Retour du système d'expérience**
Le système d'expérience fait son retour, cette fois-ci plus équitable que la fois d'avant. Les joueurs anciens étaient avantagés par rapport aux récents.

Le système d'expérience va récompenser  les "jeunes" joueurs qui sont plus actifs que des "anciens" joueurs. (Les joueurs anciens seront quand même récompensés pour leur ancienneté).

Eventuellement récompenser les joueurs qui réussisent un iputedemere sur une cible, ou un ifart, .... à réfléchir cette partie est encore en reflexion (vos propositions sont les bienvenues)

Détails du calcul d'expérience (à venir) :
- Je vais me renseigner sur le sujet, j'aimerais limiter les trop hauts niveaux (moi, goulth, etc...) et avoir un ensemble de niveau homogène. Donc peut être délibérement grandement amputer nos niveaux et nous donner à contrario un boost d'exp majeur sur une plus long durée.


<br />
<br />
<br />

### Update 4 - Wheel of Fortune 
--- 
#### Retour du iDaily
*L'économie du serveur se porte plutôt bien actuellement, après plusieurs reset, cela fait bientôt 1 année que le système a été reset et les joueurs actifs n'atteignent pas des sommes exagérées. Ainsi très peu sera touché du côté du idaily avec son système de sponsor.
*

<br />
<br />
> [!WARNING]
Une **réduction de 25-50% des soldes** en soniums sur l'entiereté des joueurs est quand même à prévoir afin d'accueillir les prochaines fonctionnalités et éviter un départ trop avancé.


<u>Ce qui se rajoute dans l'économie :</u> 
- Toute transaction va être traçée, que ce soit en provenance d'un iFart, idaily, iswift... tout sera noté dans la bdd.
- Avec l'update 0.6, les transactions idaily vont aussi être traçée et le sponsor sera directement relié à son compte sonium.



<br />
<br />
<br />


### Update 5 - Weather Forecast
---
#### Retour du module météo et ajout du module info-news.
Le module météo revient pimpé et plus cohérent, il a vite été délaissé la dernière fois, il prends trop de place et trop d'informations inutilement, il faut le rendre plus subtile.

De plus, un flux d'information continu sera mis en place pour des infos politiques, économiques, technologiques...


<br />
<br />
<br />



### Update 6 - Emperor
---
#### Machine Learning
On attaque notre première très grosse fonctionnalité sur Meeps qui va le faire passer dans une autre dimension, le **Machine learning**. 

Meeps interagirait directement avec les utilisateurs pour répondre aux questions, etc...

Actuellement il est prévu de former Meeps seulement sur les messages du discord. Peut être que ca ne sera pas suffisant et faire appel à des données externes 


<br />
<br />
<br />


### Update 7 - Notorious B.I.G
---
#### Système de haut-faits
Avec toutes les données stockées sur la BDD, il va maintenant être possible de mettre en place un système de hauts-faites, achievements avec à la clé des PPs, rôles, titres, soniums...

Exemple de hauts-faits :
- Envoyer 100 messages dans le channel général.
- Votre mère a été une pute 100x.
- Vous avez été la cible de 100 iFart.
- ....


<br />
<br />
<br />

### Update XXX (non défini) - Jail House Lock
---
Celle-là va plaire à tout les membres sauf moi. L'ajout d'un casier judiciaire et une augmentation de la puissance du tribunal où les membres seront capables de sanctionner les abus de pouvoir, irrespect. Une amende pourra être sanctionnée et un casier judiciaire sera associé à chaque joueur.


<br />
<br />
<br />

A venir :
--
De très grosses fonctionnalités sont à prévoir cette année :
- **Data analysis**. 
- Le **classement de l'aigreur** : Un message aléatoire sera exposé aux membres du serveurs qui pourront évaluer, de manière anonyme, l'aigreur du message, le joueur se verra attribué une note médianne de son aigreur. 
  
- **Un système RPG**: j'ai réussi à mettre la main sur une énorme base de données conçue par des joueurs RPG, dedans on y trouve des tables entières d'objets avec une valeur attribuée. Avec le système de sonium et le système d'expérience, je peux mettre en place une véritable architecture DnD like sur le serveur, mais c'est très long à faire.


<br />
<br />
<br />

Refonte du reboot de Meeps :
--
Avec le reset journalier ayant lieu à 8h00 tout les matins, ca serait cool d'avoir un ordre du jour qui donne la météo du jour, des news importantes, le sponsor du idaily, et autres...


<br />
<br />
<br />


Mis de côté pour le moment // je ne sais pas à quelle update les greffer:
--
-  Le système de bardes : des bots jouant de la musique 24h/24 dans un channel sans interruption. Les membres peuvent custom ces playlists à volonté selon leur goûts.
- Donation sonium : un user peut dépenser des soniums pour envoyer Meeps dire un message vocal dans un channel.
- Traqueur de jeux vidéos : permet de traquer les défaites, victoires, etc d'un joueur sur un jeu donné (Web scrapping)
- Rotation de channels : chaque jour, des channels spécifiques vont être désignés pour être accessible par l'entièreté des joueurs.
- 
