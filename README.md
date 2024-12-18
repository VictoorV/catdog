# catdog

Le dataset est constitué d'images de chiens et chats de taille 128x128. Les images sont fortement parasitées soit par un flou de mouvement, soit pas un bruit sel poivre. Les CNN sont très performants pour distinguer chat et chien sur des images nettes d'au moins 224*244 pixels. Les principaux problèmes ici sont la faible résolution des images et la très mauvaise qualité des images où il est parfois impossible à l'oeil nu de différencier chien et chat ou même de trouver l'animal.
L'objectif était d'atteindre une accuracy d'au moins 91%. Différentes techniques de filtrage ont été utilisées lors du preprocessing pour réduire le bruit des images et améliorer les prédictions du modèle. Les étapes de traitement d'images ont permis d'améliorer l'accuracy du modèle d'au moins 10%.

              precision    recall  f1-score   support

           0     0.9348    0.9180    0.9263      1000
           1     0.9194    0.9360    0.9277      1000

    accuracy                         0.9270      2000
   macro avg     0.9271    0.9270    0.9270      2000
weighted avg     0.9271    0.9270    0.9270      2000

![image](https://github.com/user-attachments/assets/64764415-f8db-49e8-baa0-d0139c03f56b)
