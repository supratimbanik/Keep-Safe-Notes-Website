# KeepSafe | A Note Storage website

**KeepSafe** is a secure, user-friendly platform for storing personal notes online. This website allows users to conveniently save, edit, and organize their notes in one place, ensuring data security and easy accessibility.

## Demo

🔗 [ KeepSafe Notes](https://keep-safe-notes.netlify.app/)

## Features

- **Create Notes:** Users can create new notes by providing a title and content. Notes are saved securely in the application.
- **Update Notes:** Users can edit the title and content of existing notes.
- **Delete Notes:** Users can delete notes they no longer need. A confirmation dialog is displayed before deleting to prevent accidental deletions.
- **User Authentication:** Users can log in to the application to access their notes. Each user's notes are associated with their account.
- **Responsive Design:** The application is designed to be responsive and works well on various devices and screen sizes.

## Installation

Clone the repository:

```bash
git clone https://github.com/supratimbanik/Keep-Safe-Notes-Website.git
```

Install dependencies:

```bash
npm install
```

Install dependencies:

```bash
cd KeepSafe
npm install
```

**Frontend setup**

Set up environment variables:

Create a `.env` file in the root directory and add the following variables:

```
REACT_APP_BASE_URL=<base-url>
```

Replace `<base-url>` with the base URL of your backend server.

Start the frontend application:

```bash
cd src
npm start
```

This will start the frontend server.

**Backend Setup**

Set up environment variables:

Create a `.env` file in the `backend` directory and add the following variables:

```
DATABASE=<database-api-key>
```

Replace `<database-api-key>` with the your mongodb database api URI.

Start the server application:

```bash
cd backend
node server.js
```

## Authors

- [@supratimbanik](https://github.com/supratimbanik)

## Tech Stack

![REACT](https://shields.io/badge/react-black?logo=react&style=for-the-badge)

![NODE](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white)

![MONGODB](https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white)

![EXPRESS](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=fff&style=flat)
