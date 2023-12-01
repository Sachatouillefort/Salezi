# Intégration de Strapi avec Grafana Dashboard
 
Ce projet démontre comment intégrer Strapi, un CMS headless open-source, avec Grafana, une plateforme d'analyse et de surveillance. En combinant ces deux outils puissants, vous pouvez visualiser et analyser les données de votre application Strapi de manière efficace.
 
## Configuration requise
 
Assurez-vous d'avoir installé les prérequis suivants avant de commencer :
 
- [Strapi](https://strapi.io/) - Un CMS headless basé sur Node.js
- [Grafana](https://grafana.com/) - Une plateforme d'analyse et de surveillance
 
## Installation
 
**Installation**
1. Clone Repository
 
    ```bash
    git clone git@github.com:Sachatouillefort/Salezi.git
    npm run develop
    ```
 
2. **Grafana Setup**
   - Install Grafana following the official documentation instructions.
    - Configure Grafana and ensure it is running.
 
        ```bash
        # Start Grafana
        sudo service grafana-server start
        ```
 
3. **Configuration de la source de données Grafana pour Strapi**
   - Dans Grafana, ajoutez une nouvelle source de données.
   - Sélectionnez le type de source de données comme "Strapi".
   - Configurez les paramètres de connexion avec l'URL de votre instance Strapi.
 
4. **Importation du Dashboard Grafana**
   - Importez le tableau de bord Grafana pré-configuré fourni dans le répertoire `grafana-dashboard` de ce projet.
   - Personnalisez les panneaux en fonction de vos besoins spécifiques.
 
5. **Lancement de l'application**
   - Démarrez votre application Strapi et assurez-vous que Grafana est en cours d'exécution.
 
   ```bash
   # Lancement de l'application Strapi en mode développement
   npm run develop
   ```
 
## Utilisation
 
Accédez à Grafana et ouvrez le tableau de bord Strapi pour visualiser les métriques et les statistiques de votre application Strapi.
 
##  Collection Postman
   - Utilisez la collection Postman fournie dans le répertoire `postman-collection` pour tester les différentes routes de votre application Strapi.
 
 
## Contributions
 
Les contributions sont les bienvenues ! Si vous trouvez des problèmes ou souhaitez améliorer cette intégration, n'hésitez pas à ouvrir une issue ou à soumettre une demande de fusion.
 
## Auteurs
 
- Sacha Gaulin and Steven - Développeur principal
---
