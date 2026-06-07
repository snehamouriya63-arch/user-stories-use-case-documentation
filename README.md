# User Stories & Use Case Documentation

## Project Title

Login System for an E-Commerce Mobile Application

---

## 1. Feature Selection

### Feature: User Login System

The login system allows users to securely access their accounts using their registered email address and password.

---

## 2. User Stories

### User Story 1

**As a customer, I want to log in using my email and password so that I can securely access my account.**

#### Acceptance Criteria

* User can enter a valid email address.
* User can enter a valid password.
* User is redirected to the dashboard after successful login.
* Error message is displayed for invalid credentials.

---

### User Story 2

**As a customer, I want to reset my password so that I can regain access if I forget it.**

#### Acceptance Criteria

* User can click the "Forgot Password" link.
* Password reset email is sent to the registered email address.
* User can create a new password.
* User can log in successfully using the new password.

---

### User Story 3

**As a customer, I want the system to remember my login details so that I do not need to log in every time I open the application.**

#### Acceptance Criteria

* "Remember Me" checkbox is available.
* User remains logged in after closing and reopening the application.
* Login session expires according to security policy.

---

### User Story 4

**As an administrator, I want to view user login activity so that I can monitor account access and security.**

#### Acceptance Criteria

* Admin can view login history.
* Login date and time are displayed.
* User information is visible to authorized administrators only.

---

### User Story 5

**As a customer, I want to receive an error message for incorrect login attempts so that I know why access was denied.**

#### Acceptance Criteria

* Error message appears for invalid credentials.
* Message does not reveal sensitive account information.
* User can retry login.

---

## 3. Use Case Documentation

### Use Case Name

User Login

### Primary Actor

Customer

### Goal

Access personal account securely.

### Preconditions

* User must have a registered account.
* User must have valid login credentials.

### Main Flow

1. User opens the application.
2. User enters email address.
3. User enters password.
4. User clicks Login.
5. System validates credentials.
6. System grants access.
7. User is redirected to dashboard.

### Alternative Flow

1. User enters invalid credentials.
2. System displays error message.
3. User re-enters credentials.

### Postconditions

* User successfully accesses the application dashboard.

---

## 4. Use Case Diagram

```
            +----------------+
            |     System     |
            +----------------+
                   |
                   |
              (Login)
                   |
                Customer
                   |
     -----------------------------
     |                           |
```

(Forgot Password)          (Remember Me)
|
Reset Password

Actor: Customer

Use Cases:

* Login
* Forgot Password
* Reset Password
* Remember Me

---

## 5. Conclusion

The Login System enables secure authentication for customers accessing the e-commerce application. The documented user stories clearly define business requirements, while the acceptance criteria establish measurable conditions for successful implementation. The use case documentation and diagram provide developers with a clear understanding of user interactions and system behavior.
