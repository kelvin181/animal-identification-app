# Animal Identification App

## Description
This app allows users to upload a photo of an animal, which is then processed using the OpenAI API to identify the species and other information. Once identified, the app maps the sighting location on a map, enabling users to view sightings of various animals globally. 

## Features
* Upload and identify animals in photos.
* Utilizes the OpenAI API for accurate animal recognition.
* Maps animal sightings on an interactive map.
* Use the filter to view sightings of a specific animal species.

# Prerequisites
Before running the app, ensure you have the following installed:
* Node.js
* npm

## Installation and Setup
#### 1. Clone the repository:
```
git clone https://github.com/kelvin181/animal-identification-app.git
cd <repository-folder>
```
#### 2. Install dependencies:
```
npm install
```
#### 3. Set up the environment file:
Create a `.env` file in the root directory of the project with the following variables:
```
# OpenAI API Key
VITE_OPENAI_API_KEY=your_openai_api_key
OPENAI_API_KEY=your_openai_api_key

# Firebase Configuration
VITE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_project_id.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_firebase_project_id.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
VITE_FIREBASE_APP_ID=your_firebase_app_id
VITE_FIREBASE_MEASUREMENT_ID=your_firebase_measurement_id

# Tenor API Key
VITE_TENOR_APIKEY=your_tenor_api_key
```
Fill in the values with your API keys and Firebase project configuration details.
  
#### 4. Run the backend server:
```
node index.js
```

#### 5. Run the frontend server:
```
npm run dev
```

#### 6. Access the app:
Open your browser and navigate to the URL of the development server (e.g. `http://localhost:5173/`).
