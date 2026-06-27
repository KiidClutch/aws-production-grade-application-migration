# Production-Grade AWS Application Migration

Production-grade migration of a Node.js Employee Directory application from an on-premises Linux server to AWS using Amazon EC2, Amazon RDS, AWS Database Migration Service (DMS), AWS Secrets Manager, Application Load Balancer, and Elastic Beanstalk.

---

## Architecture

<img width="1433" height="955" alt="image" src="https://github.com/user-attachments/assets/f8daf0c8-5a8a-4a44-b1ae-983ffa1f091a" />

---

## Project Overview

This project demonstrates an end-to-end production-grade application migration from an on-premises environment to AWS. The application was migrated to Amazon EC2, the MySQL database was migrated to Amazon RDS using AWS DMS, credentials were secured with AWS Secrets Manager, traffic was routed through an Application Load Balancer, and the application was deployed using AWS Elastic Beanstalk.

---

## AWS Services Used

* Amazon EC2
* Amazon RDS (MySQL)
* AWS Database Migration Service (DMS)
* AWS Secrets Manager
* Application Load Balancer (ALB)
* AWS Elastic Beanstalk
* Amazon VPC
* IAM

---

## Skills Demonstrated

* Cloud Migration
* Production Architecture
* Linux Administration
* Networking
* High Availability
* Database Migration
* IAM
* Secrets Management
* Application Deployment
* Troubleshooting

---

## Project Highlights

* Built a production-grade AWS architecture
* Designed a custom VPC with public and private subnets
* Configured Amazon RDS Multi-AZ deployment
* Migrated data using AWS Database Migration Service (DMS)
* Secured credentials using AWS Secrets Manager
* Implemented an Application Load Balancer
* Deployed the application with AWS Elastic Beanstalk
* Validated the migration end-to-end

---

## Documentation

Detailed documentation is available here:

[View Full Project Documentation](documentation/AWS_Production_Grade_Application_Migration_Portfolio.pdf)

---

## Source Code

The application source code is located in the `source/` directory.

### Project Structure

```text
source/
├── public/
│   ├── app.js
│   ├── index.html
│   └── styles.css
├── sql/
│   └── init.sql
├── db.js
├── package.json
├── package-lock.json
└── server.js
```

The application includes:

- **Node.js** backend using Express
- **MySQL** database connectivity
- **AWS Secrets Manager** integration for secure database credentials
- REST API endpoints for managing employees
- Responsive HTML, CSS, and JavaScript frontend

---

## Repository Structure

```text
aws-production-grade-application-migration/
│
├── README.md
├── LICENSE
│
├── architecture/
│   └── production-architecture.png
│
├── documentation/
│   └── AWS_Production_Grade_Application_Migration_Portfolio.pdf
│
├── screenshots/
│
└── source/
```

---

## Future Enhancements

Potential improvements include:

- CI/CD deployment with GitHub Actions
- Infrastructure as Code using Terraform
- Amazon CloudWatch monitoring
- HTTPS using AWS Certificate Manager
- Custom domain with Amazon Route 53
- Containerized deployment using Docker and Amazon ECS/EKS

---

## Author

**Dwayne Cowart**

AWS Cloud Engineer

📧 dcowart87@gmail.com

LinkedIn: www.linkedin.com/in/dwayne-cowart

GitHub: *(add your GitHub profile link)*

