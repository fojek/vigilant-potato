# vigilant-potato
Capteur WiFi générique pour la cabane

* WIFI : ESP-12F ou ESP-M3
* MCU : Atmel ou ESP ou STM
* DC/DC à partir d'une alimentation 24V
* Adresse modifiable, par exemple DIP switch rotative

* Possibilité de lire: 
- distance ; 
- température ; 
- pression ;
- 2 entrées digitales ;

* Possibilité d'écrire :
- deux sorties relais?

Capteur ultrason modulaire (et autres capteurs)

Affichage de l'état : 
 - Vert clignotant : ON et en train de se connecter
 - Vert solide : ON et connecté
 - Autre led : Rouge si erreur (ou la même avec une autre séquence)
 - Autre led : trig effectué (distance)

Todo
- [ ] Déterminer un format
- [ ] Choisir ESP et MCU
- [ ] Choisir capteur ultrason
- [ ] Fabriquer PCB et tester
