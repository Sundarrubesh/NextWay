# Next Way - Career Guidance System

## Overview

Next Way is a comprehensive career guidance system designed to assist 12th standard students in making informed decisions about their future academic and professional paths. The project utilizes a combination of Python, HTML, CSS, JavaScript, Bootstrap, and various Azure services, such as Azure Resource Group, Web App, Virtual Network integration, VNet Monitor, AI Language, and Bot Services.

## Features

- **User-Friendly Interface:** Intuitive and user-friendly interface for seamless user experience.
  
- **AI-Driven Career Recommendations:** Personalized career recommendations using AI Language services.

- **Educational Course Suggestions:** Recommends relevant educational courses for chosen career paths.

- **Azure Integration:** Utilizes Azure services for scalability, security, and reliability.
  - **Azure Resource Group:** Manages and organizes resources in a resource group for easy management.
  - **Azure Web App:** Hosts the web application for a scalable and reliable user experience.
  - **Virtual Network Integration:** Ensures secure and isolated communication between components.
  - **VNet Monitor:** Monitors the Virtual Network for performance and security.
  - **AI Language Services:** Leverages Azure's AI capabilities for personalized recommendations.
  - **Bot Services:** Integrates chatbot functionality for real-time assistance and queries.

## Azure Services Explanation

### Azure Resource Group

Azure Resource Group is a logical container for resources deployed on Azure. It helps in organizing and managing related resources in a unified manner. In this project, the Resource Group is used to group and manage the various Azure resources required for Next Way.

### Azure Web App

Azure Web App is a fully managed platform for building, deploying, and scaling web apps. In Next Way, it hosts the application, providing a scalable and reliable platform for users to access career guidance services.

### Virtual Network (VNet)

Virtual Network enables secure communication between different components of the application. By integrating a Virtual Network, Next Way ensures that data transmission is isolated and secure, enhancing the overall system's reliability.

### VNet Monitor

VNet Monitor is a tool that helps monitor the performance and security of the Virtual Network. It ensures that the communication within the Virtual Network is optimized and secure, providing a stable environment for the application.

### AI Language Services

Azure's AI Language services are employed to power the AI-driven features of Next Way. These services analyze user inputs, interests, and skills to generate personalized career recommendations, enhancing the overall user experience.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/next-way.git


## Installation

To run NEXTWAY locally on your machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/NextWay/NEXTWAY.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database:

   ```bash
   # Assuming you have a DBMS installed, create a database for NEXTWAY
   # Update the database configurations in config.py
   python manage.py db init
   python manage.py db migrate
   python manage.py db upgrade
   ```

4. Run the application:

   ```bash
   python app.py
   ```

Visit [http://localhost:5000](http://localhost:5000) in your web browser to access NEXTWAY locally.

