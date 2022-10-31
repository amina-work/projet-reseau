# projet-reseau

Module : réseau de capteurs et algorithme distribué

Application : détection des feux de forêt

Description : 
En utilisant la technologie WSN, nous créerons une application pour détecter et contrôler les feux de forêt. Les réseaux de capteurs peuvent être utilisés efficacement à cette fin. Le feu en tout lieu peut être considéré comme un événement et la détection de tels événements peut être effectuée à l’aide de réseaux de capteurs. Les paramètres tels que la température supérieure à une certaine valeur seuil (que nous fournissons?) viennent simplement sous l’événement. Les nœuds de capteurs feront rapport aux sink une fois que les événements de données correspondent à leurs tâches. 

Nos nœuds de capteurs collaboreront pour transporter les données de l’événement du lieu de son occurrence à l’évier, qui peut être placé à un endroit éloigné. le sink traitera ensuite les données et prendra les mesures nécessaires. Cependant, afin de transporter les données d’événement, un protocole de routage fiable et efficace est nécessaire, qui peut économiser de l’énergie (les nœuds de capteurs sont limités en termes de puissance de transmission).