# Blogging App Backend

This is the backend of the Blogging App, a platform where users can read, write, and share articles. The backend is built using Node.js, Express, and MongoDB.

## Features

- User authentication (login, registration)
- Create, edit, delete, and view articles
- Comment on articles
- User profile management
- Admin dashboard for managing posts, comments, and users

## Project Structure
blogging-app-backend/ ├── .gitignore ├── LICENSE ├── README.md ├── package.json ├── server.js ├── config/ │ ├── db.js │ └── default.json ├── controllers/ ├── middleware/ ├── models/ ├── routes/ └── utils/


## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher) or yarn (v1.22 or higher)
- MongoDB

### Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/blogging-app-backend.git
cd blogging-app-backend

Install dependencies:

npm install
# or
yarn install

Set up environment variables:
Create a .env file in the root directory and add the following variables:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Running the Project
Start the development server:
npm run dev
# or
yarn dev

This will start the development server on http://localhost:5000.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.

Contact
For any inquiries, please contact suryascodeverse@example.com or chauhanaman1912@gmail.com