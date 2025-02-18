# SavStore
![p](https://github.com/user-attachments/assets/5a508e6f-fa93-4ff8-8849-6da331ab3bec)

## Storage and File Sharing Platform

Build this project step by step with our detailed tutorial on JavaScript Mastery YouTube. Join the JSM family!

## 📋 Table of Contents
- 🤖 Introduction
- ⚙️ Tech Stack
- 🔋 Features
- 🤸 Quick Start
- 🕸️ Snippets (Code to Copy)
- 🔗 Assets

## 🤖 Introduction
SavStore is a storage management and file-sharing platform that lets users effortlessly upload, organize, and share files. Built with the latest Next.js 15 and the Appwrite Node SDK, it utilizes advanced features for seamless file management.

## ⚙️ Tech Stack
- React 19
- Next.js 15
- Appwrite
- TailwindCSS
- ShadCN
- TypeScript

## 🔋 Features
- **User Authentication with Appwrite**: Implement signup, login, and logout functionality using Appwrite's authentication system.
- **File Uploads**: Effortlessly upload a variety of file types, including documents, images, videos, and audio, ensuring all your important data is stored securely.
- **View and Manage Files**: Users can browse through their uploaded files stored in Appwrite storage, view them in a new tab, rename files, or delete them.
- **Download Files**: Users can download their uploaded files, giving them instant access to essential documents.
- **File Sharing**: Users can easily share their uploaded files with others, enabling collaboration and easy access to important content.
- **Dashboard**: Gain insights at a glance with a dynamic dashboard that showcases total and consumed storage, recent uploads, and a summary of files grouped by type.
- **Global Search**: Quickly find files and shared content across the platform with a robust global search feature.
- **Sorting Options**: Organize files efficiently by sorting them by date, name, or size, making file management a breeze.
- **Modern Responsive Design**: A fresh and minimalist UI that emphasizes usability, ensuring a clean aesthetic across all devices.
- **More**: Leverages the latest React 19, Next.js 15, and Appwrite features with a focus on code architecture and reusability.

## 🤸 Quick Start
Follow these steps to set up the project locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository
```sh
git clone https://github.com/Dhrumit26/SavStore.git
cd SavStore
```

### Installation
Install the project dependencies using npm:
```sh
npm install
```

### Set Up Environment Variables
Create a new file named `.env.local` in the root of your project and add the following content:
```sh
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""
```
Replace the values with your actual Appwrite credentials. You can obtain these credentials by signing up and creating a new project on the Appwrite website.

### Running the Project
```sh
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## 🕸️ Snippets
- `tailwind.config.ts`
- `globals.css`
- `constants/index.ts`
- `lib/utils.ts`
- `index.d.ts`

## 🔗 Assets
Assets used in the project can be found [here](#).

