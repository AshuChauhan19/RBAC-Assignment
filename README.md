# RBAC-Assignment

In this project ,I have 3 folder 
1-> Backend
2-> Dashboard(Admin)
3-> Frontend(Users)



Backend Setup

1->Clone the repository and navigate to the backend folder:
git clone https://github.com/yourusername/liaplus-ai.git
cd liaplus-ai/backend

2-> Install dependencies:
npm install

3->Create a .env file in the backend/ folder:

APP_DEBUG=true
APP_ENVIRONMENT=local
PORT=7000
JWT_SECRET=lia_plus_ai
JWT_EXPIRY=1h

# Mongo DB Credentials
DB_CONNECTION=mongodb
DB_HOST=127.0.0.1
DB_PORT=27017
DB_DATABASE=lia_plus_ai
DB_USERNAME=
DB_PASSWORD=

# Email
GMAIL_USER=ashuchauhan.hastree@gmail.com
GMAIL_PASS=***jpnt wnwy kwof jtcw***

4-> Start the backend server:
npm start

Server will run at: http://localhost:7000




5->Navigate to the frontend folder:

6-> Install dependencies:
npm install

7-> Start the frontend server:
npm start

