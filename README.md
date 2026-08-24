# EX-5 CLOUD DATA STORAGE SERVER
CLOUD DATA STORAGE SERVER
# REG NO : 212224040270
# NAME : RANJANA R

## AIM

To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

## ALGORITHM

1. Log in to the AWS Management Console.
2. Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.
3. Create a DB Subnet Group with subnets in two Availability Zones.
4. Launch an Amazon RDS MySQL Multi-AZ DB instance.
5. Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.
6. Open the provided web application using the Web Server IP.
7. Enter the RDS endpoint, database name, username, and password.
8. Connect the application to the database.
9. Test the application by adding, editing, viewing, and deleting records.

## OUTPUT

<img width="922" height="910" alt="Screenshot 2026-08-19 173759" src="https://github.com/user-attachments/assets/2d803391-3186-4828-95e8-5778ff497c29" />
<img width="935" height="906" alt="Screenshot 2026-08-19 174224" src="https://github.com/user-attachments/assets/485cd21e-bdea-4030-9a96-b3a79a04c05d" />
<img width="1505" height="486" alt="Screenshot 2026-08-19 175928" src="https://github.com/user-attachments/assets/992fd42a-a765-4c0f-b0bd-a7cb3d2750e4" />
<img width="1619" height="500" alt="Screenshot 2026-08-19 183019" src="https://github.com/user-attachments/assets/6e323ed5-5fb9-4a36-b5ab-2017def95460" />
<img width="1280" height="860" alt="Screenshot 2026-08-19 183111" src="https://github.com/user-attachments/assets/6413d798-d10b-4a1a-8ae9-ac66a5066b85" />
<img width="964" height="648" alt="Screenshot 2026-08-19 183318" src="https://github.com/user-attachments/assets/fd386e67-ad22-46d0-a33c-b1bc53eac270" />

## RESULT

The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.
