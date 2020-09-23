# Projet_integration
## Objectif

Permettre aux personnes âgées, isolées de rester connecter via des photos/vidéos/messages avec leurs familles.

## Comment ?

La famille envoie des photos,vidéos,messages via une application sur smartphone, la personne isolé les reçoit et les visualise sur un écran ( tv,.. ) connecté à une boîte ( raspbery pi,.. )

## Technologies possibles ? 

pour l'application mobile on pourrait partir sur du réact ou du nodejs qui sont simple d'utilisation et avec beaucoup de documentation:

- du côté de react, il y a **react native** et **ionic react** : 
    
    1. ionic react :
        
        Ionic React est d'abord Web, ce qui signifie qu'il implémente des modèles d'interface utilisateur iOS et Android natifs à l'aide d'une technologie Web
        multiplateforme basée sur des normes au lieu d'accéder directement aux contrôles de l'interface utilisateur de la plate-forme.
        
        **Avantage(s) :**     Applications Web React traditionnelles.
                              Offre à un développeur web un développement rapide et familier (peut se faire directement dans chrome).
                              Facilement ajouté à n'importe quelle application React existante sur le Web.
                              react DOM (bibliothèque) 
        
        
        **Désavantage(s) :**  Les performances nécéssaire sont plus élevée.
        
    2. react native :
        
        React Native fournit une abstraction via React qui contrôle directement les contrôles de l'interface utilisateur de la plate-forme. 
        Utilise principalement des controleurs ios et android. 
       
        **Avantage(s) :**     Performances plus élevée (dépends des cas) 
                              L'interfaçage est plus simple
                              support personnalisé pur le debugging 
                              plate-forme et écosystème autonomes
        
        **Désavantage(s) :**  Les controles sont plus difficile à personnaliser
                              Les techniques standard css, html et dom ne peuvent pas être utilisée 
                              Les bibliothèques react existantes ne sont probablement pas portables vers react native sans personnalisation  
                              Nécessite un émulateur ou un appareil pour le débugging  
        
        
    src: https://ionicframework.com/resources/articles/ionic-react-vs-react-native 
