# projet-reseau

Module : réseau de capteurs et algorithme distribué

Application : détection des feux de forêt

Description : 
En utilisant la technologie WSN, nous créerons une application pour détecter et contrôler les feux de forêt. Les réseaux de capteurs peuvent être utilisés efficacement à cette fin. Le feu en tout lieu peut être considéré comme un événement et la détection de tels événements peut être effectuée à l’aide de réseaux de capteurs. Les paramètres tels que la température supérieure à une certaine valeur seuil (que nous fournissons?) viennent simplement sous l’événement. Les nœuds de capteurs feront rapport aux sink une fois que les événements de données correspondent à leurs tâches. 

Nos nœuds de capteurs collaboreront pour transporter les données de l’événement du lieu de son occurrence à l’évier, qui peut être placé à un endroit éloigné. le sink traitera ensuite les données et prendra les mesures nécessaires. Cependant, afin de transporter les données d’événement, un protocole de routage fiable et efficace est nécessaire, qui peut économiser de l’énergie (les nœuds de capteurs sont limités en termes de puissance de transmission).

## Mots Clés:
Réseau de type MANET
Algorithme distribué
Routage Dynamic, a état de lien, OSLR

 Les réseaux MANET sont modélisés par des graphes de disques. (UDG, DGU, DGB) 
 Il faut aussi modéliser la mobilité des nœuds  Il est nécessaire de modéliser le déplacement des nœuds 
 Modèle de mobilité 
 Recalculer à chaque fois le graphe de disques résultant

### OLSR 
OLSR stands for Optimized Link State Routing Protocol. In this, each node periodically floods status of its links. Each node re-broadcasts link state information received from its neighbors. Each node keeps track of link state information received from other nodes. Each node uses above information to determine next hope to each destination. It is proactive and table-driven.