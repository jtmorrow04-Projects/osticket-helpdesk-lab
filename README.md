#### Project Overview

The **IT Help Desk Lab** is a hands-on learning project designed to build practical experience in IT support, systems administration, and IT service management. Using osTicket, Docker Desktop, Docker Compose, and MySQL, this project focuses on setting up a help desk environment and exploring how IT support operations are managed.

The initial environment was configured by following an existing installation guide, which I adapted for a Windows environment using Command Prompt and Docker Desktop. Building on that foundation, I am working to expand my understanding of containerized applications, database connectivity, technical troubleshooting, and help desk workflows.

Planned activities include simulating real-world support tickets involving hardware, software, networking, and account access; documenting troubleshooting steps and resolutions; and developing knowledge base articles. This project provides an opportunity to apply concepts learned through guided setup, hands-on experimentation, and independent troubleshooting.

### Installation Guide & Credits

This project was initially set up using the following guide:

- **Guide Creator:** Gilbert Sanchez
- **Original Guide:** How I Built a Help Desk System for $0 https://www.youtube.com/watch?v=JIMw4Kjp2vg

### Application Architecture

This lab uses a containerized architecture consisting of a web-based help desk application and a database backend.

- **Frontend / Web Application** — osTicket: Provides the user interface for submitting, viewing, and managing IT support tickets. It is accessed locally at http://localhost:8080.

- **Admin / Staff Panel** — osTicket Staff Control Panel: The administrative interface used by help desk staff to manage tickets, review requests, assign work, and configure support workflows. Accessible at http://localhost:8080/scp.

- **Backend / Database*** — MySQL: Stores application data, including ticket and user information, and supports the osTicket application.

Both services are configured through Docker Compose and run as separate containers managed by Docker Desktop.


Credit is given to the original creator for the installation instructions that served as the foundation for this lab. Any adaptations, additional documentation, troubleshooting notes, and extensions will be documented as the project progresses.
