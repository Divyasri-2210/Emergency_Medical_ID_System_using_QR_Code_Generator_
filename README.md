
# 🏥 Web-Based Emergency Medical ID System Using QR Code

## 📌 Project Overview

The Web-Based Emergency Medical ID System Using QR Code is a web application designed to provide quick access to essential medical information during emergency situations.

The system allows users to register, log in, create medical profiles, and generate unique QR codes linked to their medical information. When the QR code is scanned, authorized emergency viewers can access important details such as blood group, allergies, medical conditions, and emergency contact information.

The main goal of this project is to help emergency responders access critical medical information quickly and support timely medical assistance.

## 🎯 Objectives

- To provide quick access to essential medical information.
- To generate unique QR codes for individual users.
- To maintain patient medical records digitally.
- To reduce delays in accessing important medical details during emergencies.
- To provide a simple and user-friendly web interface.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend Programming |
| Flask | Web Framework |
| MySQL | Database Management |
| HTML5 | Frontend Structure |
| CSS3 | User Interface Design |
| JavaScript | Frontend Functionality |
| QR Code | Medical Information Access |
| Git & GitHub | Version Control |

## ✨ Key Features

### 1. User Registration
- Allows new users to create an account.
- Collects basic personal information.

### 2. User Login
- Provides secure user authentication.
- Allows registered users to access their profiles.

### 3. Medical Profile Management
- Stores essential medical information.
- Includes blood group, allergies, medical conditions, and emergency contacts.
- Supports adding, viewing, editing, and updating records.

### 4. QR Code Generation
- Generates a unique QR code for each medical profile.
- Connects the QR code to the corresponding emergency medical information.

### 5. Emergency Medical Information
- Enables emergency viewers to access important medical details by scanning the QR code.
- Helps emergency responders identify critical patient information.

## 🔄 System Workflow

1. The user registers on the application.
2. The user logs into the system.
3. The user enters personal and medical information.
4. The information is stored in the MySQL database.
5. The application generates a unique QR code.
6. During an emergency, the QR code can be scanned.
7. The linked emergency medical profile displays the available medical information.

## 📂 Project Structure

```text
Emergency-Medical-ID-System/
│
├── app.py
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── profile.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│
├── database/
│   └── database.sql
│
├── requirements.txt
├── README.md
└── .gitignore
```

*Note: The folder structure above is a suggested structure. Adjust it to match the actual project files.*

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone <your-github-repository-url>
```

### Step 2: Navigate to the Project Directory

```bash
cd Emergency-Medical-ID-System
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**
```bash
venv\Scripts\activate
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Configure MySQL Database

- Install and start MySQL.
- Create a database for the project.
- Import the SQL file if provided.
- Configure the database credentials in the Flask application.

### Step 6: Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

## 🔐 Security Considerations

- Protect user login credentials.
- Use password hashing.
- Avoid exposing sensitive medical information publicly.
- Restrict access to medical records.
- Use HTTPS when deploying the application.
- Ensure QR codes do not expose unnecessary personal information.

## 🚀 Future Enhancements

- Mobile application integration.
- Emergency SMS notifications.
- Hospital and ambulance integration.
- Advanced authentication mechanisms.
- Cloud-based medical record storage.
- Multilingual support.

## 👨‍💻 Developer Information

**Name:** Pagadala Madhu

**Role:** Data Scientist

**Project:** Web-Based Emergency Medical ID System Using QR Code

## 📜 Conclusion

The Web-Based Emergency Medical ID System Using QR Code provides a convenient way to access essential medical information during emergency situations. By combining web technologies, database management, and QR code generation, the system aims to improve the accessibility of critical medical details and support faster emergency response.

---

⭐ If you find this project useful, consider giving the repository a star!
