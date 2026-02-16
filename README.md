# smart-lost-found-recovery-system
A centralized, AI-driven web platform developed using Django and MongoDB to automate the reporting, matching, and recovery of lost and found items within institutions.

**Smart Lost and Found Item Recovery System**

**Project Overview**

The Smart Lost and Found Item Recovery System (SS-LIT) is a digital platform designed to streamline the inefficient process of manual loss-reporting in community or institutional environments. It replaces traditional logbooks with an automated matching mechanism that uses AI-based text similarity and object detection to connect lost items with their finders.

**Key Features**

• User Management: Secure registration and login with email/OTP verification to ensure account authenticity.

• Smart Reporting: Users can submit detailed reports for lost or found items, including item name, category, location, descriptions, and images.

• AI-Powered Matching:

    ◦ Utilizes YOLOv8 for advanced image-based detection and recognition.
    ◦ Implements text similarity algorithms to automatically flag potential matches between descriptions.
    
• Admin Dashboard: A centralized portal for administrators to verify AI-suggested matches, manage recovery logs, and track system statistics.

• Automated Notifications: Sends real-time email alerts and confirmation messages to users once a potential match is identified or verified.

• Security & Transparency: Includes role-based access control, secure password hashing (bcrypt), and TLS 1.3 encryption for data transfers.

**System Architecture**

The system follows a three-tier layered design for maximum scalability:

1. Frontend Layer: Built with HTML, CSS, Bootstrap, and JavaScript for a responsive user interface.
 
2. Backend Layer: Powered by Django (Python) to manage application logic and authentication.
 
3. Database Layer: Uses MongoDB (NoSQL) for flexible storage of unstructured data like item descriptions and images.
 
4. AI Engine: Integrates YOLO and feature extraction models for similarity detection.
   
**Development Methodology**

This project was developed using the Agile methodology, specifically the Scrum framework, dividing the lifecycle into manageable sprints for iterative feature delivery and continuous testing.

Sustainable Development Goals (SDG) Alignment
This system contributes to the following UN SDGs:

• Goal 11 (Sustainable Cities and Communities): Enhancing safety and community responsibility.

• Goal 12 (Responsible Consumption and Production): Encouraging item reuse and minimizing waste.

• Goal 16 (Peace, Justice, and Strong Institutions): Establishing transparency through digital audit logs.

**Technical Stack**

• Framework: Django (Python 3.x)

• Database: MongoDB

• AI Models: YOLOv8, SequenceMatcher

• Communication: SMTP for Email/OTP

• Testing: Pytest (Backend) and Jest (Frontend)
