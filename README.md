# D8S AI-driven dashboards

## Project Overview
**D8S AI-driven dashboards** is a solution that automates the collection and presentation of key data from various systems by building a scraping tool that retrieves information from REST APIs. For systems lacking a REST API, Node-exporter can be installed. The dashboards are based on a **need-to-know** principle – if there are no alerts, the dashboard remains black.

## Key Components:
1. **Data Collection**:
    - By using an advanced scraper that integrates with REST APIs from various platforms, relevant data is automatically and continuously collected.

2. **Database**:
    - All collected data is stored in a structured database, allowing you to work with both historical and real-time data.
    - The data is used to create dashboards that provide insights over time, not just snapshots.

3. **Dashboard Design**:
    - **Target Audience**: The dashboards are aimed at decision-makers such as CTOs, operations managers, and C-level executives who need quick and clear insights into the organization's IT operations.
    - **Features**: The dashboards will be extremely simple to understand and will contain a maximum of five key metrics, tailored to provide a clear overview without unnecessary complexity.
    - **Examples**:
      - "C-level Dash for Kubernetes Cluster" can display key metrics such as the number of active nodes, resource usage, pod performance, and any errors.
      - "C-level Dash for DORA Metrics" can highlight important DevOps metrics such as deployment frequency, lead time for changes, failure rate, and time to restore services.

## Use Cases and Customer Benefits
- **For DevOps Teams**: A DevOps team can use the dashboards to monitor key metrics that impact development and operations processes.
- **For C-level Executives**: High-level decision-makers can quickly understand the operation and performance of their IT environments without needing to dive into technical details.
- **For Business Analysts**: By presenting historical data and real-time information, analysts can draw conclusions and make data-driven decisions for optimization and improvement.

## Technology and Tools
- **Languages and Frameworks**: Python will be used to build scrapers and handle data, while the frontend for the dashboards can be built using popular libraries like React or Vue.js. The backend may include Flask or Django for API management.
- **Databases**: PostgreSQL, MySQL, or NoSQL solutions like MongoDB can be used to store the data.
- **Visualizations**: Tools like Grafana, Dash, or custom solutions built with JavaScript can be used to create dashboards that are both functional and visually appealing.

## Summary
**D8S AI-driven dashboards** provide valuable and accessible information to both technical and non-technical decision-makers. The project focuses on simplicity and efficiency, with dashboards that offer clear insights through relevant metrics and data visualizations.
