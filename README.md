# Video Conferencing App

This repository contains a secure, real-time video conferencing application built using Next.js, Firebase, Shadcn/ui, and Tailwind CSS. The application replicates core functionalities of popular video conferencing platforms, providing integrated video and messaging capabilities.

## Features

- **Real-time Video Conferencing**: Allows users to join and host meetings with live video and audio streams.
- **Secure User Authentication**: Utilizes Clerk for secure user authentication and session management.
- **Real-time Messaging**: Integrated GetStream.io to enable real-time messaging within the application.
- **Scalable Backend Infrastructure**: Leveraged Firebase for efficient session handling and data storage.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS, Shadcn/ui
- **Backend**: Firebase
- **Authentication**: Clerk
- **Real-time Messaging**: GetStream.io

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/akanksha509/Video-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd video-conferencing-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Configure Firebase and Clerk API keys.
5. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

- Visit `http://localhost:3000` to access the app.
- Sign up or log in using the authentication system.
- Create or join a video conference room.
- Use the chat feature to communicate in real-time.

## Demo

[https://video-app-sepia.vercel.app/](https://video-app-sepia.vercel.app/)
