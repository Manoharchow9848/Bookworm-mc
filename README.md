# Bookworm-MC
================

A brief description of the project goes here.

## Table of Contents
-----------------

* [About](#about)
* [Features](#features)
* [Installation](#installation)


## About
--------

Bookworm-MC is a Minecraft mod that brings a love of reading to the world of blocks. This mod adds a new dimension of literary exploration, allowing players to discover and interact with books in a whole new way.

## Features
Here are some potential features for the Bookworm-MC project:

Core Features

Book Collection: Players can collect and store books in their inventory, and trade them with other players.
Bookshelves: Players can build and customize their own bookshelves, using a variety of materials and designs.
Library Generation: The mod generates libraries and bookstores in the game world, filled with books and other literary treasures.
Reading Mechanics: Players can read books to gain knowledge, experience, and other benefits.
Item Features

Books: Players can craft and collect books on various subjects, including magic, history, and science.
Quills and Ink: Players can craft writing tools to create their own books and write notes.
Bookmarks: Players can craft bookmarks to keep their place in their favorite books.
Block Features

Bookshelves: Players can build bookshelves to store and display their book collection.
Library Blocks: Players can build libraries and bookstores using special blocks.
Reading Desks: Players can build reading desks to study and read books.
Gameplay Features

Literary Quests: Players can complete quests and challenges related to reading and literature.
Author NPCs: Players can meet and interact with author NPCs, who can offer quests and rewards.
Book Clubs: Players can join book clubs to discuss and share books with other players.
Customization Features

Book Covers: Players can customize the covers of their books using various materials and designs.
Bookshelves Skins: Players can customize the appearance of their bookshelves using various skins.
Reading Settings: Players can customize their reading experience, including font size, color, and more.
These are just some ideas, and you can add or remove features as you see fit to suit your project's goals and vision.

## Installation
------------

# Bookworm-MC Installation Guide

## Prerequisites
Ensure you have the following installed before proceeding:
- Node.js (>=16.x)
- npm or yarn
- Expo CLI (for React Native)
- Android Studio (for Android) or Xcode (for iOS)

---

## Backend (Node.js + Express.js)

### 1. Clone the Repository
```sh
git clone https://github.com/Manoharchow9848/Bookworm-mc.git
cd bookworm-mc/backend
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Set Up Environment Variables
Create a `.env` file in the `backend` directory and add the necessary environment variables:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### 4. Start the Backend Server
```sh
npm run dev
```
The server should now be running on `http://localhost:5000`.

---

## Frontend (React Native)

### 1. Navigate to the Frontend Directory
```sh
cd ../mobile
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Set Up Environment Variables
Create a `.env` file in the `frontend` directory and add:
```
API_BASE_URL=http://localhost:5000
```

### 4. Start the React Native App
```sh
npx expo start
```
- Scan the QR code with the Expo Go app (Android/iOS) to run the app on your device.

---

## Additional Notes
- Ensure MongoDB is running before starting the backend.
- For production, update `.env` with your live API URLs and database credentials.
- Use `npm run dev` instead of `npm start` for hot reloading in development.

Happy coding! 🚀



