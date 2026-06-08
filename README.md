# 🎓 Student Management Portal

A responsive **Student Management Portal** built using **HTML, CSS, JavaScript, and Bootstrap 5**. This project provides a user-friendly interface for managing student-related information through multiple pages, including registration, dashboard, profile management, and contact support.

> **Note:** This is a front-end project that uses **LocalStorage** to simulate authentication and user profile management without a backend.

---

## 🚀 Features

### 🏠 Home Page (`index.html`)

* Modern hero section with institution branding
* Feature cards highlighting portal services
* Student login modal with LocalStorage-based session simulation
* Dark/Light mode toggle with persistent theme preference

### 📝 Student Registration (`registration.html`)

* Fully responsive registration form
* Bootstrap validation support
* Student details collection, including:

  * Full Name
  * Roll Number
  * Email Address
  * Mobile Number
  * Gender
  * Branch
  * Date of Birth
  * Address
  * Profile Photo Upload
  * Terms & Conditions Agreement

### 📊 Student Dashboard (`dashboard.html`)

* Dashboard overview with summary cards
* Student records table
* Real-time search functionality to filter students by name

### 👤 Student Profile (`profile.html`)

* Displays logged-in student information
* Retrieves data directly from LocalStorage
* Provides a personalized profile view

### 📞 Contact Us (`contact.html`)

* Responsive contact form
* Client-side form submission feedback
* Success notification upon form submission

---

## 🛠️ Tech Stack

| Technology       | Purpose                      |
| ---------------- | ---------------------------- |
| HTML5            | Structure and Content        |
| CSS3             | Custom Styling               |
| Bootstrap 5.3.8  | Responsive UI Components     |
| JavaScript (ES6) | Interactive Features         |
| LocalStorage     | Client-Side Data Persistence |

---

## 📂 Project Structure

```text
Student-Management-Portal/
│
├── index.html
├── registration.html
├── dashboard.html
├── profile.html
├── contact.html
├── styles.css
│
├── images/
│   └── (project assets)
│
└── screenshots/
    └── (application screenshots)
```

---

## ⚙️ Getting Started

### Prerequisites

* Any modern web browser (Chrome, Edge, Firefox, Safari)
* Optional: VS Code with Live Server Extension

### Run Locally

1. Clone the repository:

```bash
git clone https://github.com/your-username/student-management-portal.git
```

2. Navigate to the project folder:

```bash
cd student-management-portal
```

3. Open `index.html` in your browser.

### Recommended Method

Use **VS Code Live Server** or any lightweight local server to ensure assets load correctly and provide a smoother development experience.

---

## 💾 LocalStorage Usage

This project uses the browser's LocalStorage to simulate user authentication and profile management.

### Stored Data

The login form saves the following information:

```javascript
studentName
rollNumber
branch
email
mobile
isLoggedIn
```

### Functionalities

* User login simulation
* Profile data retrieval
* Theme preference persistence
* Session-like user experience

---

## 🌙 Dark Mode Support

The application includes a Dark Mode toggle that:

* Saves user preference in LocalStorage
* Automatically restores the selected theme on page reload
* Applies a custom `dark-mode` class to the `<body>` element

---

## 🔍 Dashboard Search

The dashboard includes a dynamic search feature that:

* Filters student records instantly
* Searches based on student names
* Improves usability for larger datasets

---

## 📸 Screenshots

Screenshots demonstrating the application's interface are available in the `screenshots/` directory.

Included views:

* Home Page
* Registration Page
* Dashboard
* Student Profile
* Contact Page
* Mobile Responsive Layout

---

## 🎯 Future Enhancements

* Backend Integration (Node.js / PHP / Django)
* Database Support (MySQL / MongoDB)
* User Authentication System
* Attendance Management Module
* Results & Grades Management
* Admin Dashboard
* Student Notifications
* REST API Integration

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is intended for **educational and demonstration purposes**.

Feel free to use, modify, and enhance it for learning and academic projects.

---

### ⭐ If you found this project useful, consider giving it a star on GitHub!
