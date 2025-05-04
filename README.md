Real-time Disaster Alert System

📌 Overview

The Real-time Disaster Alert System is a full-stack, cloud-native web application designed to monitor, analyze, and notify users of natural disasters such as earthquakes, floods, and wildfires in real time. Leveraging the power of Azure Functions, Azure Maps, and Azure Communication Services, this system delivers timely alerts to users based on their location and preferences.

🎯 Key Features

Live Disaster Tracking:  Pulls data from trusted sources like USGS and GDACS via Azure Functions.

Interactive Map Dashboard:  Visualizes disaster locations using Azure Maps and allows filtering by type and severity.

Custom Alert Preferences:  Users can specify their location, disaster types of interest, and notification method (SMS/email).

Scalable Notifications:  Sends real-time alerts through Azure Communication Services when relevant events occur nearby.

Serverless & Scalable:  Built using serverless Azure services, ensuring scalability and low maintenance.

☁️ Azure Services Used

Azure Service	Purpose
Azure Functions	Serverless backend to fetch, process, and classify disaster data
Azure Maps	Interactive frontend map visualization
Azure Cosmos DB	Stores disaster event data and user preferences
Azure Communication Services	Sends SMS/email alerts based on user location and disaster severity
Azure Static Web Apps	Hosts the frontend React application

🧠 Optional AI Enhancements

Severity Prediction: ML model to predict escalation risk based on past patterns.

Text Classification: NLP models to extract relevant info from unstructured sources (e.g., Twitter or news feeds).

📦 Tech Stack Summary

Layer	Technology
Frontend	React, Azure Maps SDK, Tailwind CSS
Backend	Azure Functions (Node.js / Python)
Database	Azure Cosmos DB (MongoDB API)
Notifications	Azure Communication Services
Hosting	Azure Static Web Apps
