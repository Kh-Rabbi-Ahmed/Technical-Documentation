# Queue Management Application

This folder contains the detailed technical scope, architecture, and deployment guidelines for the **Queue Management Application**.

## Documents:
1. **Queue Management Application Technical Scope**: A comprehensive document that outlines the deployment architecture, including load balancing, database replication, high availability, disaster recovery, and monitoring strategies. [Link to Document](Queue-Management.pdf)
2. **EBL Cloud Diagram**: A diagram representing the cloud architecture for the application, showcasing the components involved in the system’s deployment. [Link to Diagram](Cloud-Diagram.pdf)

### Key Features:
- **High Availability**: Nginx Load Balancer, Kubernetes (K3S) for auto-scaling, and MySQL replication for database high availability.
- **Disaster Recovery (DR)**: DR environments in geographically separated regions with automated failover and data synchronization.
- **Microservices**: Services deployed using K3S with Kong Ingress for API management.
- **Security**: SSL termination, firewall configurations, and Keycloak for authentication and authorization.

### Deployment Environment:
- **Production (Prod)**: Live environment with secure and highly available services.
- **User Acceptance Testing (UAT)**: A testing environment to validate new features before production deployment.
- **Disaster Recovery (DR)**: A replicated environment to ensure continuity during system failures.

---

## How to Contribute:
Feel free to contribute by submitting pull requests or adding improvements related to the Queue Management system.


