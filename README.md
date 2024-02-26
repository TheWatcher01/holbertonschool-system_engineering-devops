# Web Infrastructure Design Project

## Overview
This project involves the design of a simple yet robust web infrastructure. The goal is to understand the basic components of a web infrastructure and how they interact with each other to deliver a web application.

## Design Requirements
The web infrastructure design should meet the following criteria:

1. **Single Server**: Utilize one server to host all components of the web stack.
2. **Web Server (Nginx)**: Implement Nginx as the web server to handle HTTP requests.
3. **Application Server**: Include an application server to run the application logic.
4. **Application Files**: Ensure the presence of application files (code base) on the server.
5. **Database (MySQL)**: Incorporate a MySQL database for data storage.
6. **Domain Name**: Use the domain name foobar.com with a www record pointing to the server IP 8.8.8.8.

## Infrastructure Explanation
- **Server**: A dedicated or shared machine that hosts our web application and its components.
- **Domain Name**: Acts as a human-readable address (foobar.com) that maps to the server's IP address.
- **DNS Record**: The 'www' in www.foobar.com is a DNS record that helps in mapping the domain name to the server's IP.
- **Web Server (Nginx)**: Handles HTTP requests from clients and serves web pages.
- **Application Server**: Executes the application's backend logic.
- **Database (MySQL)**: Stores and manages the application's data.

## Potential Issues
- **Single Point of Failure (SPOF)**: Since all components are on a single server, any failure impacts the entire service.
- **Maintenance Downtime**: The need to restart the web server during updates or maintenance can lead to service unavailability.
- **Scalability**: Difficulty in handling increased traffic due to the single-server setup.

## Conclusion
This project serves as an introductory step into understanding web infrastructures. It highlights the importance of each component and the challenges faced in a simple web infrastructure setup.