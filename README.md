# Azure Database for PostgreSQL Single Server & Flexible Server Inventory Dashboard

This sample dashboard enables you to easily manage your Azure Database for PostgreSQL Single and Flexible Server.

![dashboard](img/azure-postgresql-single-to-flexible-dashboard.png)

It includes:

- Number of Single and Flexible Server
- MySQL Version
- SKU
- Service Tier
- Location
- Network Configurations
- Backup Configurations
- HA/DR Configurations
- etc

## How to install the dashboard

1. Download "azure-postgresql-single-to-flexible-dashboard.json" file from this repository
2. Go to https://portal.azure.com
3. Ensure that you can access to the subscription that has Azure Arc-enabled Servers and SQL Servers
4. Go to dashboard, click "Upload", select "azure-postgresql-single-to-flexible-dashboard.json"

![howto](img/howto.png)