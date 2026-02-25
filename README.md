\# 📇 Contact Keeper



A full-stack Contact Management Application built using \*\*Node.js (Express)\*\* for the backend and \*\*Flutter\*\* for the frontend.



This application allows users to securely manage personal and professional contacts with authentication and database integration.



---



\## 🚀 Features



\- User Registration \& Login

\- Secure Authentication (JWT)

\- Add New Contacts

\- Update Existing Contacts

\- Delete Contacts

\- RESTful API Integration

\- MongoDB Database

\- Cross-platform Flutter UI



---



\## 🛠️ Tech Stack



\### 🔹 Backend

\- Node.js

\- Express.js

\- MongoDB

\- Mongoose

\- JSON Web Token (JWT)

\- dotenv



\### 🔹 Frontend

\- Flutter

\- Dart



---



\## 📂 Project Structure



```

contact-keeper/

│

├── contact\_app\_backend/

│   ├── models/

│   ├── middleware/

│   ├── server.js

│   ├── package.json

│   └── .env (not pushed)

│

├── contact\_app\_frontend/

│   ├── lib/

│   ├── android/

│   ├── ios/

│   ├── web/

│   └── pubspec.yaml

│

├── .gitignore

└── README.md

```



---



\## ⚙️ Installation \& Setup



\### 1️⃣ Clone the Repository



```bash

git clone https://github.com/your-username/contact-keeper.git

cd contact-keeper

```



---



\### 2️⃣ Backend Setup



```bash

cd contact\_app\_backend

npm install

npm start

```



Create a `.env` file inside `contact\_app\_backend`:



```

MONGO\_URI=your\_mongodb\_connection\_string

JWT\_SECRET=your\_secret\_key

```



---



\### 3️⃣ Frontend Setup



```bash

cd contact\_app\_frontend

flutter pub get

flutter run

```



---



\## 🔐 Environment Variables



The backend requires the following environment variables:



| Variable     | Description |

|-------------|------------|

| MONGO\_URI   | MongoDB connection string |

| JWT\_SECRET  | Secret key for JWT authentication |



---



\## 📌 Future Improvements



\- Contact search functionality

\- Profile image upload

\- Deployment (Render / Firebase)

\- Role-based authentication

\- API documentation (Swagger)



---



\## 👩‍💻 Author



\*\*Naveena\*\*



---



\## ⭐ If You Like This Project



Give it a star on GitHub ⭐

