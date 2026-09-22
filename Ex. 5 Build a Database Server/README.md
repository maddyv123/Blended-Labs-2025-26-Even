# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**:Mathavan V
* **Register Number**: 212223110026
* **Date of Submission**: 25.08.2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)
I opened the AWS Management Console and navigated to the EC2 Dashboard.
I checked the existing EC2 instance and noted its Availability Zone.
I opened Elastic Block Store (EBS) → Volumes and created a new EBS volume in the same Availability Zone as the EC2 instance.
I selected a suitable volume type such as General Purpose SSD (gp3) and specified the required storage size.
After creating the volume, I selected it and used Attach Volume to attach it to my running EC2 instance.

## Output Screenshots
<img width="1837" height="873" alt="Screenshot 2026-08-21 154910" src="https://github.com/user-attachments/assets/0891a777-433d-4d19-a96a-d229f97f3571" />
<img width="1600" height="1019" alt="image" src="https://github.com/user-attachments/assets/f59ce489-3b90-4fbd-a801-fea3597ccd3b" />

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
