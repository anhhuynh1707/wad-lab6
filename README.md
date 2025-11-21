# LAB 6: AUTHENTICATION & SESSION MANAGEMENT
#### 📄 STUDENT INFORMATION:

Name: Huỳnh Tuấn Anh

Student ID: ITITIU23003

Class: WAD_G01_Lab03_Tue1234

#### 📚 COMPLETED EXERCISES:

✔ Exercise 1: Database & User Model

✔ Exercise 2: User Model & DAO

✔ Exercise 3: Login/Logout Controllers

✔ Exercise 4: Views & Dashboard

✔ Exercise 5: Authentication Filter

✔ Exercise 6: Admin Authorization Filter

✔ Exercise 7: Role-Based UI

✔ Exercise 8: Change Password

#### AUTHENTICATION COMPONENTS:
- Models: User.java
- DAOs: UserDAO.java
- Controllers: LoginController.java, LogoutController.java, DashboardController.java
- Filters: AuthFilter.java, AdminFilter.java
- Views: login.jsp, dashboard.jsp, updated student-list.jsp

#### 🧪 TEST CREDENTIALS:
Admin:
- Username: admin
- Password: password123

Regular User:
- Username: john
- Password: password123

#### 🔎 FEATURES IMPLEMENTED:
- User authentication with BCrypt
- Session management
- Login/Logout functionality
- Dashboard with statistics
- Authentication filter for protected pages
- Admin authorization filter
- Role-based UI elements
- Password security

#### 🔐 SECURITY MEASURES:
- BCrypt password hashing
- Session regeneration after login
- Session timeout (30 minutes)
- SQL injection prevention (PreparedStatement)
- Input validation
- XSS prevention (JSTL escaping)

#### ❗ KNOWN ISSUES:
- [List any bugs or limitations]

#### BONUS FEATURES:
- [List any bonus features implemented]

⌚ **TIME SPENT:** 6 hours

#### TESTING NOTES:
[Describe how you tested authentication, filters, and authorization]
