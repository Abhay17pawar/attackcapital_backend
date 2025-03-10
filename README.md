
# Backend Setup for Attack Capital


This is the backend of the Attack Capital project, which serves as the API for managing blog posts, user authentication, and other related features.


## Prerequisites

Before running the backend, ensure that you have the following software installed on your system:

* Node.js: LTS version or higher
* MongoDB (Local or a cloud-based MongoDB service like MongoDB Atlas)
* Git (For version control and cloning repositories)


## Installation

1. Clone the Repository
```bash
git clone https://github.com/Abhay17pawar/attack-capital.git

```
2. Install Dependencies
```bash
cd backend
npm install

```
3. Set up Environment Variables

Create a .env file in the root of the backend directory and add the following environment variables:
```bash
PORT=
MONGODB_URI=
JWT_SECRET=your_jwt_secret_key
```
* PORT: The port your backend will run on (e.g., 5000).
* MONGODB_URI: MongoDB connection string (local or cloud-based).
* JWT_SECRET: A secret key used to sign JSON Web Tokens (JWT).

If you're using MongoDB Atlas, make sure to replace the MONGODB_URI with your cloud MongoDB connection string.

4. Run the Backend

Once the dependencies are installed and environment variables are set, you can start the backend server:

```bash
npm start
```
## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

