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
VITE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=1:666417253972:web:
VITE_FIREBASE_MEASUREMENT_ID=G-
VITE_TENOR_APIKEY=
VITE_OPENAI_API_KEY=
OPENAI_API_KEY=
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
