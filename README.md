Le code contenu dans ce repository est le code d'un proscreener basé sur les Moyennes mobiles longues : SMA100, SMA150, SMA200.
Il détecte les actifs qui répondent aux conditions suivantes :

- Le cours de clôture croise au-dessus de la SMA100 ou est égal à SMA100 ou le plus bas de la bougie actuelle est égal à SMA100.
- La SMA100 est supérieure à SMA200.
- La SMA100 est en tendance haussière.
- Le volume est supérieur ou égal à 10000.
- Les SMA100, SMA150 et SMA200 sont alignées dans l'ordre croissant pour une période d'alignement spécifiée (alignPeriod = 10), 

Le langage utilisé est ProRealcode, un langage propre à la plateforme de Trading Prorealtime.
Ci-dessous des exemples d'actions détectées par le screener.



Exemple sur l’action INPOST au 30/07/2024 :
￼
![Capture d’écran 2024-07-30 à 20 42 24](https://github.com/user-attachments/assets/3ea883e5-17b2-43b4-b223-0c0ffd4cd527)


Exemple sur l’action LISI au 30/07/2024 :

![Capture d’écran 2024-07-30 à 20 42 38](https://github.com/user-attachments/assets/1a24d29e-8240-4148-8e34-6eb25ba83f2c)
