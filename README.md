# Group6 
GROUP CONTRIBUTION BY INDIVIDUALS 
1. CALEB  DUNYO
2. ABIGAIL ODONKOR 
3. FRANCIS ECHESI 
4. ISRAEL ANSAH OWUSU 
5. JOSEPH AGERE 
6. KWAME OSEI TUTU AGYEMAN 

Requirements
Docker: Ensure Docker is installed on your machine. Docker Compose, required for orchestrating our multi-container setup, is included with Docker Desktop for Windows and Mac. For Linux, Docker Compose might need to be installed separately.
Setup
Clone the Repository
bash git clone https://github.com/Data-Engineering-Training/Group6.git cd Group6Project

Configure Environment Variables (Optional)
Create a .env file in the project root for custom configurations:

env MYSQL_ROOT_PASSWORD=your_secure_password MYSQL_DATABASE=your_database_name MYSQL_USER=your_database_user MYSQL_PASSWORD=your_user_password PHPMYADMIN_PORT=8080

Launch the Containers
bash docker-compose up -d

Access phpMyAdmin
Open http://localhost:8080 (or your custom port) and log in with the MySQL credentials.
