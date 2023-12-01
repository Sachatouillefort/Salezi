Integration of Strapi with Grafana Dashboard

This project demonstrates how to integrate Strapi, an open-source headless CMS, with Grafana, an analytics and monitoring platform. By combining these two powerful tools, you can efficiently visualize and analyze data from your Strapi application.

**Prerequisites**
Make sure you have installed the following prerequisites before getting started:

- Strapi - A Node.js-based headless CMS.
- Grafana - An analytics and monitoring platform.

**Installation**
1. Clone Repository

    ```bash
    git clone git@github.com:Sachatouillefort/Salezi.git
    npm run develop
    ```

2. Grafana Setup

    - Install Grafana following the official documentation instructions.
    - Configure Grafana and ensure it is running.

        ```bash
        # Start Grafana
        sudo service grafana-server start
        ```

3. Configure Grafana Data Source for Strapi

    - In Grafana, add a new data source.
    - Select the data source type as "Strapi."
    - Configure connection settings with the URL of your Strapi instance.

4. Import Grafana Dashboard

    - Import the pre-configured Grafana dashboard provided in the grafana-dashboard directory of this project.
    - Customize panels according to your specific needs.

**Launching the Application**

Start your Strapi application and ensure Grafana is running.

```bash
# Launch Strapi application in development mode
npm run develop
```

**Usage**

Access Grafana and open the Strapi dashboard to visualize metrics and statistics from your Strapi application.

**Postman**

Use the provided Postman collection in the postman-collection directory to test different routes of your Strapi application.

**Contributions**

Contributions are welcome! If you encounter issues or want to improve this integration, feel free to open an issue or submit a pull request.

**Authors**

- Sacha Gaulin and Steven Guillermet - Lead Developers
