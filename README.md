# 🔐 Simple Login Registration GUI

<p align="center">
  <strong>A clean and user-friendly login and registration application built with Python and Tkinter</strong>
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/121743449/235904340-25275a0e-9a30-410d-88c9-27127080ad56.png" alt="Login Screen" width="40%" />
  <img src="https://user-images.githubusercontent.com/121743449/235904585-4cffe6be-5145-4c2c-8294-664bddcb565d.png" alt="Registration Screen" width="40%" />
</p>

---

## 📋 Features

✨ **User-Friendly Interface**

- Clean, intuitive GUI built with Tkinter
- Responsive layout with proper spacing and alignment

🔑 **Authentication**

- Login functionality with validation
- User registration with email verification
- Password confirmation matching

✅ **Input Validation**

- Username validation (6-20 alphanumeric characters + underscore)
- Password strength requirements (minimum 6 characters)
- Email validation (Gmail format)
- Real-time error feedback with visual indicators
- Auto-clear error messages when user starts typing

🎨 **User Experience**

- Success/failure notifications
- Smooth navigation between login and registration screens
- Error messages displayed directly in input fields
- Color-coded feedback (red for errors, cyan for buttons)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Tkinter (included with most Python installations)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dotrainier/Simple-Login-Registration-Gui-Python-.git
   cd Simple-Login-Registration-Gui-Python-
   ```

2. **Run the application:**
   ```bash
   python "Login&SignUp.py"
   ```

---

## 📝 Usage

1. **Launch the application** - The login screen will appear
2. **Create an account** - Click "Register Now" to create a new account
3. **Enter your details:**
   - Username (6-20 characters, alphanumeric + underscore)
   - Password (minimum 6 characters)
   - Confirm Password (must match)
   - Email (Gmail format required)
4. **Login** - Use your credentials to log in
5. **Success** - Upon successful login/registration, you'll see a confirmation screen

### Validation Rules

| Field            | Requirements                                        |
| ---------------- | --------------------------------------------------- |
| Username         | 6-20 characters (letters, numbers, underscore)      |
| Password         | Minimum 6 characters (letters, numbers, underscore) |
| Confirm Password | Must match the password field                       |
| Email            | Valid Gmail address (example@gmail.com)             |

---

## 🏗️ Project Structure

```
.
├── Login&SignUp.py          # Main application file
└── README.md                # This file
```

### Key Functions

- `myLogin()` - Displays the login window
- `myRegister()` - Displays the registration window
- `validating_Login_Reg()` - Validates all user inputs
- `showSuccesfull_Login()` - Shows login success screen
- `showSuccesfull_Registation()` - Shows registration success screen

---

## 🛠️ Technologies Used

- **Python 3** - Programming language
- **Tkinter** - GUI framework for creating desktop applications
- **Regular Expressions (re)** - Input validation

---

## 📌 Notes

- This is a GUI prototype demonstration
- Currently, credentials are not persisted to a database (for production use, integrate a database like SQLite or PostgreSQL)
- Email validation requires Gmail addresses
- All validation errors are displayed with ⚠️ emoji indicators

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest improvements
- Submit pull requests

---

## 📄 License

This project is open source and available for educational and personal use.

---


