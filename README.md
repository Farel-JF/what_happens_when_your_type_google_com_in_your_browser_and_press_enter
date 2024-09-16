# What happens when you type https://www.google.com in your browser and press Enter

## Overview

This project explores the various steps involved when you enter a URL in your browser and hit "Enter." It is a common interview question that helps assess a candidate's understanding of the web stack and how the internet works behind the scenes. The project covers essential concepts such as DNS, TCP/IP, firewalls, SSL, load balancing, and how web servers interact with application servers and databases.

## Concepts Covered

- **DNS Request**: How the domain name is translated into an IP address through the Domain Name System.
- **TCP/IP**: The communication protocols that allow data to be transmitted over the internet.
- **Firewall**: How security layers protect the infrastructure by controlling incoming and outgoing network traffic.
- **HTTPS/SSL**: The encryption mechanisms used to secure communication between the browser and the server.
- **Load Balancer**: The role of load balancers in distributing traffic across multiple servers.
- **Web Server**: How the web server handles HTTP requests and responds to the client.
- **Application Server**: The server responsible for generating dynamic content and processing business logic.
- **Database**: How the application server interacts with the database to retrieve or store data.

## Tasks

### 0. What happens when...
Write a detailed blog post explaining each step of what happens when you type `https://www.google.com` in your browser and press Enter. The post should cover the following topics:
- DNS request
- TCP/IP
- Firewall
- HTTPS/SSL
- Load-balancer
- Web server
- Application server
- Database

**Blog post URL**: [Link to Blog Post]

### 1. Everything's better with a pretty diagram
Create a diagram that illustrates the flow of the request when you type `https://www.google.com` in your browser. The diagram should include the following elements:
- DNS resolution
- Request hitting server IP on the appropriate port
- Traffic encryption
- Traffic passing through a firewall
- Request distribution via a load balancer
- Web server responding with a web page
- Application server generating the web page
- Application server requesting data from the database

**Diagram URL**: [Link to Diagram]

## Repository Structure

```bash
holbertonschool-network/
└── what_happens_when_your_type_google_com_in_your_browser_and_press_enter/
    ├── README.md
    ├── 0-blog_post
    └── 1-what_happen_when_diagram
