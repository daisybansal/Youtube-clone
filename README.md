# YouTube Clone Project

A full-stack YouTube clone application built with Next.js, Express, and Firebase.

## Project Structure

The project consists of three main services:
- `yt-web-client`: Frontend web application built with Next.js
- `video-processing-service`: Backend service for video processing
- `yt-api-service`: API service built with Firebase Functions

## Prerequisites

- Node.js (version 18 or higher)
- Firebase account and CLI
- Google Cloud account with necessary APIs enabled
- FFmpeg for video processing

## Setup Instructions

1. Clone the repository
2. Install dependencies for each service

3. Configure Firebase
- Create a new Firebase project
- Copy your Firebase config to `yt-web-client/firebaseconfig.ts`
- Set up Firebase authentication
- Configure Firestore database
- Set up Firebase storage

4. Environment Variables
Create `.env` files in each service directory with the necessary configurations.

## Running the Application

1. Start the web client

2. Start the video processing service

3. Start the API service


## Features

- User authentication
- Video upload and processing
- Video playback
- Responsive design
- Real-time updates

## Technologies Used

- Next.js
- Express
- Firebase (Authentication, Firestore, Storage)
- FFmpeg
- TypeScript
- Google Cloud Storage
