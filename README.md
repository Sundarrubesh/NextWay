# NextWay
# Project NEXTWAY

Welcome to NEXTWAY, your personalized guide to finding the right college based on your career selection. This web application is designed for higher secondary school students who are exploring their options for higher education. NEXTWAY is built using the Python Flask framework for the backend and incorporates a database management system (DBMS) to efficiently store and retrieve data.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Pages](#pages)


## Introduction

As a higher secondary school student, choosing the right college can be a daunting task. NEXTWAY aims to simplify this process by providing a user-friendly platform that allows students to explore colleges based on their career interests. The application is built with Python Flask, ensuring a robust and efficient system.

## Features

- **User Registration:** Students can create an account on NEXTWAY by providing their details in the registration form. This step is essential to access the detailed course information.

- **Pages:**
  - **Home Page:** Welcome to NEXTWAY, a brief overview of the platform and its purpose.
  - **About Page:** Learn more about the mission and vision of NEXTWAY.
  - **Courses Page:** Access detailed information about various colleges offering courses in arts, science, engineering, and technology.
  - **Contact Page:** Reach out to the NEXTWAY team for any inquiries or support.
  - **Service Page:** Explore additional services or features provided by NEXTWAY.
  - **Chat Bot:** An interactive chatbot to assist users in navigating the platform.
  - **Register and Login Page:** Essential for accessing personalized course information.

## Installation

To run NEXTWAY locally on your machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/NEXTWAY.git
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

## Usage

1. Register an account on the 'Register' page to unlock access to the courses page.
2. Explore colleges and courses based on your career selection on the 'Courses' page.
3. Engage with the chatbot for any assistance.
4. Contact the NEXTWAY team via the 'Contact' page for additional support or inquiries.

## Pages

- **Home Page:** https://nextway123.azurewebsites.net/
- **About Page:** https://nextway123.azurewebsites.net/about
- **Courses Page:** https://nextway123.azurewebsites.net/courses
- **Contact Page:** https://nextway123.azurewebsites.net/contact
- **Service Page:** https://nextway123.azurewebsites.net/blog
- **Chat Bot:** https://nextway123.azurewebsites.net/chat
- **Register Page:** https://nextway123.azurewebsites.net/signup
- **Login Page:** https://nextway123.azurewebsites.net/login
Feel free to explore these pages to make the most of the NEXTWAY platform.

## Contact

For any questions, feedback, or support, please contact us at [contact@nextway.com](mailto:contact@nextway.com).

Thank you for choosing NEXTWAY!

**Azure Services**

NEXTWAY is powered by various Microsoft Azure services, including:

Web App: The core of the application is hosted on Microsoft Azure's Web App service, ensuring reliable and scalable web hosting.

Virtual Network: Azure Virtual Network is utilized for efficient management and secure communication within the application's infrastructure.

AI Services: Leveraging Azure AI capabilities to enhance user experience, such as the interactive chatbot for user assistance.

Monitoring: Utilizing Azure Monitor for effective monitoring and performance management, ensuring a seamless user experience.




