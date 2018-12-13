---
title: 2) PRESENTATION DES ECRANS : Builder
layout: post
author: emilie.paniagua
permalink: /2)-presentation-des-ecrans-:-builder/
source-id: 11wsof_ZavMoWJ-C1uh6PfPlGLbMi11FHJCYg9CxG-bE
published: true
---
## **_2) PRESENTATION DES ECRANS_**

## **_4 Le BUILDER de la console _**

### Présentation : 

Il se divise en trois parties :

1. Le Playground, où l'on teste le bot

2. les Intents, qui sont des mots-clés que l'utilisateur ou le chatbot emploie pour établir la conversation. Les intents sont précédés d'un dièse.

3. les Inputs et les Outputs, propres à chaque Intent, qui sont les réponses (output) que donne le robot à chaque entrée (Input). C'est véritablement dans les Outputs que va se passer 80% de du paramétrage de la conversation.

### Boutons de base

Dans les Outputs se trouve un menu avec des items cliquables qui permettent de paramétrer l'interface : nous allons en expliquer quelques-uns : 

![image alt text]({{ site.url }}/public/JFr6t29b2CbxfzUId7S74w_img_0.png)

1. Insert variable assignment : 

Il s'agit du bouton qui va permettre de stocker et afficher des variables données par l'utilisateur au fil de la conversation.

2. Insert code : 

la syntaxe du code d'action à saisir sera action = name_of_action

Il s'agit de la ligne de code qui va permettre au bot de suivre le fil d'une conversation. Sans trop en expliquer ici, on va mettre l'action dans un premier output d'intent, et la même syntaxe dans la conditionnelle de l'output d'intent suivant, ce qui va permettre de créer un chemin conversationnel.

3. Button :

permet de créer un bouton qui va être cliquable par l'utilisateur et qui donc va permettre de standardiser les inputs. On peut créer un bouton Oui, Non, ou n'importe quel input souhaité.

4. Trash : 

Ce bouton sert à supprimer un des trois boutons énoncés ci-dessus de l'output, ce qui doit être fait en supprimant d'abord le texte interne puis en cliquant sur le bouton, puis sur la corbeille (trash)

On saisit un input ou un output en cliquant sur + en bout de ligne  et en appuyant sur Save en haut de page.

À noter que l'interface n'est pas sensible à la casse des inputs. Quand on modifie un intent, un bouton SAVE apparaît sur lequel il convient de cliquer pour sauvegarder les changements.![image alt text]({{ site.url }}/public/JFr6t29b2CbxfzUId7S74w_img_1.png)

### Ajout d'une conditionnelle

1. à noter également que ce menu propose, quand on ouvre un nouvel intent, une étoile à trois branches qu'on appelle une conditionnelle. Cette étoile est proposée tant que les outputs ne contient pas d'outputs non conditionnels. Les outputs non conditionnels préexistants ("I don't understand" par exemple), doivent donc être d’abord effacés à la main.

