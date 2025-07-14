---

## ❗ Problem Statement

Managing patient records manually in clinics often leads to:
- Long wait times.
- Misplaced or lost patient history.
- Poor coordination between doctors and receptionists.
- No quick way to retrieve data using phone number or token.

There is a need for a simple, digital solution to streamline patient registration, consultations, and billing.

---

## 🧠 Use Case

This project is designed for small to medium-sized clinics to:

- Register patients and generate unique token IDs.
- Allow doctors to access medical history and prescribe easily.
- Enable receptionists to manage billing efficiently.
- Retrieve patient details using either token ID or phone number.

---

## 🛠️ Tech Stack Used

| Category      | Technology     | Description                               |
| ------------- | -------------- | ----------------------------------------- |
| **Frontend**  | React.js       | For building interactive user interfaces  |
|               | Axios          | To handle HTTP requests                   |
|               | React Router   | For client-side routing                   |
|               | Tailwind CSS   | For fast and responsive UI styling        |
| **Backend**   | Node.js        | JavaScript runtime environment            |
|               | Express.js     | Web framework for Node.js                 |
|               | MongoDB        | NoSQL database to store patient data      |
|               | Mongoose       | MongoDB ODM for schema and query handling |
|               | JSON Web Token | For secure authentication                 |
|               | bcryptjs       | To hash and verify passwords              |
| **Dev Tools** | Nodemon        | Auto-restarts server during development   |
|               | dotenv         | To manage environment variables           |
| **Database**  | MongoDB Atlas  | Cloud-based database service              |
