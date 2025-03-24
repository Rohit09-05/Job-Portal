1.Pre-requisite:
Ensure Node.js is installed on your system.

2.Setup Instructions:
Navigate to the Project Directory:

3.Open the terminal/command prompt and go to the project directory:

cd job-portal

Navigate to the Backend Directory:
Enter the backend directory:
cd backend

5.Install Backend Dependencies:
Run the following command to install the backend dependencies:

npm install

6.Go Back to the Root Directory:
Go back to the root project directory:

cd ..

7.Navigate to the Frontend Directory:
Enter the frontend directory:

cd frontend

8.#Install Frontend Dependencies:
Install the necessary frontend dependencies:
npm install

Configuration:
Create a .env File:
In the backend folder

9.#Add the Following Environment Variables:


# Backend Server Configuration
PORT=8000  

# MongoDB Connection
MONGO_URI="mongodb+srv://<USERNAME>:<PASSWORD>@cluster0.<CLUSTER_ID>.mongodb.net/<DATABASE_NAME>"  

# Security Key
SECRET_KEY=<YOUR_SECRET_KEY>  

# Cloud Storage (Cloudinary)
CLOUD_NAME=<YOUR_CLOUDINARY_NAME>  
API_KEY=<YOUR_CLOUDINARY_API_KEY>  
API_SECRET=<YOUR_CLOUDINARY_API_SECRET>  



10.After This:
The server should now be running on localhost:8000.
The frontend (React app) can be started separately using the appropriate npm commands.
