# Uber Clone

Creating an Uber clone (with minimal functionalities)

## Project Overview

This project is a small attempt to create some basic UI functionalities of the famous app Uber using React Native and Expo. I have used React Native and Tailwind CSS for this project

## APIs

Three different APIs were used in this build..
1. Places API (to autocomplete places names in dropdown when searching)
2. Directions API (to draw path lines between origin and destination in the google map)
3. Distance Matrix API (to calculate travel time and distance between the origin and destination)

All of these APIs require a Google Maps billing account associated to a Google Cloud project, which will give you the secret API key to access the features of these APIs.

## How to proceed with the project

1. Clone into a folder
2. Open terminal, type "npm install --force"
3. Create a .env file containing the name GOOGLE_API_KEY="" <= your API key inside the quote (keep it without quotes)
4. To start project, type "expo start"
5. Open in Expo app on your phone using the QR code

If you are more used to yarn, then feel free to remove the package-lock.json file from the project.

## Future plans

I plan to create an actual backend for this project and implement the cab booked and uber eats UI part as well. Stay tuned.
