# Checkpoint_01_SB_TSSR

## **Quizz** :

**1) Pour le matériel B, connais-tu ses différences avec A ?**  

Réponse : Les différences entre le matériel B qui est un pfSense et le matériel A qui est un Switch c'est que le pfsense est un logiciel firewall et routeur et le switch est un équipement matériel. PfSense n'est pas un matériel physique comme le switch. PfSense est une solution logicielle qui transforme un ordinateur en un dispositif de pare-feu et de routage puissant.

PfSense est un **logiciel de pare-feu et de routage**, principalement utilisé pour **sécuriser les réseaux** en créant des pare-feu et des passerelles sécurisées entre des réseaux locaux et Internet.

Un Switch est un **dispositif matériel** qui sert à **relier physiquement et diriger le trafic entre différents appareils (ordinateurs, imprimantes, etc.) au sein d'un même réseau local (LAN)**.

Un switch fonctionne **au niveau de la couche 2 du modèle OSI**, également appelée la couche de liaison de données. À ce niveau, le switch utilise les adresses MAC (Media Access Control) pour diriger les paquets de données vers les bons périphériques au sein d'un réseau local (LAN).

PfSense fonctionne principalement **au niveau de la couche 3 (réseau)** et utilise les adresses IP pour acheminer les paquets de données entre différents réseaux et offrir des fonctionnalités de pare-feu et de routage avancées. Il peut également inclure des fonctionnalités de la couche 4 (transport) pour un contrôle plus fin du trafic réseau.

Le pfSense peut être déployé comme **pare-feu et routeur principal pour protéger le réseau global**, tandis que le Switch permet de **connecter les différents appareils du réseau local pour une communication interne rapide et efficace**.

**2) Que représente em0, em1, em2 ?**

Réponse : em0 c'est l'interface WAN de pfSense-1, em1 c'est l'interface LAN de pfSense-1 et em2 c'est l'interface OPT1 de pfSense-1.

