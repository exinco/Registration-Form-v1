# Registration-Form-v1
Register with easy

(Preface: After deep digging the coding using Gemini, finally this project run smoothly. Most of the error I was encountered is about permission to write into storage like Google Sheet and Google Drive when i try to insert new data and upload a photo)

Registration Form System

A modern, responsive registration form built with React that saves data directly to Google Sheets and uploads user images/PDFs to Google Drive using a Google Apps Script backend.

🚀 Features

>Responsive UI: Built with React and Tailwind CSS.

>Google Integration: Saves all form submissions to a Google Sheet.

>File Uploads: Uploads user photos to a specific Google Drive folder.

>PDF Generation: Generates and saves a PDF report of the user's registration.

>Serverless: No traditional backend required; runs entirely on Google Apps Script.


🛠️ Tech 

>StackFrontend: React, Vite, Tailwind CSS, Lucide React

>Backend: Google Apps Script (GAS)

>Database: Google Sheets

>File Storage: Google Drive


📦 Setup & Installation
Clone the repository

>git clone [https://github.com/exinco/registration-form.git](https://github.com/yourusername/registration-form.git)
cd registration-form
Install dependencies

>npm install

Configure Backend URLOpen src/App.jsx.Find const GOOGLE_SCRIPT_URL = "...".Ensure this matches your deployed Google Web App URL.

>Run Locally >npm run dev

🌐 Deployment This project is optimized for deployment on Vercel or Netlify.
>Push your code to GitHub.

>Import the repository into Vercel/Netlify.

>Deploy! (No complex build settings required; standard Vite settings work automatically).


📝 LicenseOpen source. Feel free to use and modify.
