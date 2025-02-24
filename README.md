# ChatBot Car – IBM Watson Assistant  
Ce projet vise à créer un chatbot spécialisé dans les voitures allemandes en utilisant **IBM Watson Assistant**.  

# Theorie : 

**IBM Watson Assistant** est un service d'**intelligence artificielle** développé par IBM pour créer des **chatbots intelligents** et des **assistants virtuels** capables de comprendre et de répondre aux requêtes des utilisateurs de manière naturelle.  

### 🏗️ **Comment fonctionne Watson Assistant ?**  

1. **Détection des intentions (Intents)**  
   - Watson identifie l'**intention** de l'utilisateur à partir du texte saisi.  
   - Exemple : Si un utilisateur écrit *"Quelle est la consommation de la BMW X5 ?"*, l'intention détectée pourrait être `obtenir_info_voiture`.  

2. **Reconnaissance des entités (Entities)**  
   - Les **entités** permettent d’extraire des informations spécifiques.  
   - Exemple : Dans *"Quelle est la consommation de la BMW X5 ?"*, `BMW X5` est une **entité** représentant un modèle de voiture.  

3. **Gestion des dialogues (Dialogues)**  
   - Une fois l’intention et les entités détectées, le **dialogue** guide la réponse du chatbot.  
   - Il peut poser des questions complémentaires, donner des suggestions ou appeler des API externes pour récupérer des données.  

### 🛠️ **Pourquoi utiliser Watson Assistant ?**  

✅ **Facilité d’utilisation** : Interface intuitive sans besoin de coder.  
✅ **IA puissante** : Basé sur le NLP (*Natural Language Processing*).  
✅ **Personnalisation avancée** : Possibilité d’ajouter des règles et d'interagir avec des bases de données.  
✅ **Intégrations multiples** : Compatible avec Slack, WhatsApp, sites web, et applications.  

# Pratique :
## 📂 Structure du projet  
Dans le dossier `Chat_Bot_Car`, vous trouverez :  🚗💡
- **Dialogs** : Définition des flux de conversation.  
- **Entities** : Les entités représentant des concepts clés (ex : marques, modèles, fonctionnalités).  
- **Intents** : Les intentions des utilisateurs (ex : demander des informations sur une voiture, comparer des modèles).  

## 🛠️ Technologies utilisées  
- **IBM Watson Assistant** : Pour la création et l'entraînement du chatbot.  
- **JS**: Pour l'intégration du chatbot. 

## 📖 Documentation  
Pour une meilleure compréhension, consultez le fichier **`ASSISTANT_chat.pptx`**.  

## 🚀 Installation et Configuration  
1. **Créer un service Watson Assistant** sur IBM Cloud.  
2. **Importer les fichiers JSON** de Dialogs, Entities et Intents dans Watson Assistant.  
3. **Configurer l’API** pour connecter le chatbot à une interface utilisateur ou un backend.  

## 📞 Support  
En cas de problème, contactez Lafraouzimouhssine@gmail.com
