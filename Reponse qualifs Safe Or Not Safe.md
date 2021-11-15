# Reponse qualifs Safe Or Not Safe ?.md


## Reponse qualif Inconnu


Suite à la demande de qualification sur plusieurs IP. Le retour de qualification montre que les IP :

- 88.241.161.210
- 107.174.17.141
- 104.131.11.150
- 45.123.3.54

Elles ont toutes été blacklisté et ne pourront pas recevoir de mail (Ipqualityscore) et l'ip 178.162.0.128 est malveillante (VT).
Les scores VT ne semblent pas pertinent mais permettent toutefois de corréler avec les autres sources OSINT.
Ipqualityscore indique un haut risque avec un score de fraude entre 93 et 100 sur l'ensemble des IP. On retrouve un score abuse à 4 et 6 pour les IP 104.131.11.150 et IP 178.162.0.128 et Low pour les IP 88.241.161.210, 107.174.17.141 et 45.123.3.54 (Spyse).
Le verdict est malveillant pour L'ip 104.131.11.150 et l'ip 45.123.3.54 a 56 ports ouverts (OTX).

Nous préconisons une mise en liste noire des adresses IP et une mise en place de règle sur les pare-feu.


###


Suite à la demande de qualification sur 42.249.36.52 situé en Chine. Le retour de qualification montre que 42.249.36.52 a un VT score à 0/89, un Spyse score abuse à 0 et dans Ipqualityscore le score de fraude est à 0.

A ce jour, en date du 08/11/2021, l'IP 42.249.36.52 est safe.


###########################################################################################################


## Reponse qualif Starwars

Suite à la demande de qualification sur towel.blinkenlights.nl situé au Netherland. Le retour de qualification montre que towel.blinkenlights.nl est malveillant (VT) et on retrouve deux IP associées : 213.136.8.188 et 94.142.241.111.
Le score VT est de 0/91 et 0/89, ils ne semblent pas pertinent mais permettent toutefois de corréler avec les autres sources OSINT.
On retrouve un score abuse à 7 (Spyse) ainsi qu'un score de fraude indiqué comme suspicieux à 68 (Ipqualityscore) et un port ouvert (OTX).

Nous préconisons une mise en liste noire des adresses IP ainsi que du domaine towel.blinkenlights.nl et une mise en place de règle sur les pare-feu.


###########################################################################################################


## Reponse qualif TOR

Suite à la demande de qualification sur les adresses IP 45.128.134.199 et 37.120.217.87. Le retour de qualification montre que 45.128.134.199 et 37.120.217.87 sont suspicieuses (Ipqualityscore) et elles ont 2 ports ouverts (OTX).
Le score VT est de 0/89 et 0/91 ne semblent pas pertinent mais permettent toutefois de corréler avec les autres sources OSINT. Ipqualityscore indique un risque haut avec un score de fraude à 65 et à 70. Le score abuse des IP est low (Spyse).

Nous préconisons une mise en liste noire des deux adresses IP et une mise en place de règle sur les pare-feu.
