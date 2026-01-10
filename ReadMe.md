## How to Run this Project

You do **NOT** need to install a local database. The app connects to the cloud automatically.

### Step 1: Download
1. Click the green **Code** button above -> **Download ZIP**.
2. Extract the folder.
3. Open the folder in **VS Code**.

### Step 2: Install Dependencies
Open the Terminal in VS Code (`Ctrl + ~`) and run:
```bash
dotnet restore
Step 3: Run the App
Start the server by running:

Bash

dotnet run
Wait for it to say Now listening on: http://localhost:xxxx

Step 4: Open in Browser
Hold Ctrl and click the localhost link in your terminal.

Important: How to use the App
1. Generate Fake Data (First Time Only) ---meronnn na dummy users so oki na to pero if ever di lumabas sayo edi gewch
If the database is empty, go to this URL to create 10 dummy students for the algorithm to match you with: http://localhost:YOUR_PORT/Home/Seeder (Click the "Generate" button once).

2. Sign Up & Test
Go to Sign Up.

Create an account (e.g., test@pup.edu.ph).

Complete the Profile Setup (Select subjects like Math/Programming).

The app will automatically redirect you to the Discover Page with your best matches

Tech Stack
Frontend: HTML, Bootstrap 5, Razor Views

Backend: C# ASP.NET Core MVC

Database: Google Firebase Firestore (NoSQL)

Auth: Firebase Authentication