# Simple Banking App

A secure and modern banking application built with Flask that simulates core banking operations.

## Features

- **User Authentication**
  - Secure login and registration
  - Email verification
  - Password reset functionality
  - Account status management (pending, active)
  - Rate limiting to prevent brute force attacks

- **Account Management**
  - View account balance and details
  - Transaction history
  - User profile management
  - PIN security for sensitive operations

- **Banking Operations**
  - Money transfers between accounts
  - Transfer funds by username or account number
  - 6-digit PIN verification for secure transactions
  - Transaction history tracking
  - Admin deposit functionality

- **Security Features**
  - CSRF protection
  - Password hashing
  - Rate limiting
  - Session management
  - Email verification
  - Two-factor authorization for transfers (PIN)

- **Admin Features**
  - User account management
  - Deposit funds to user accounts
  - View system transaction history
  - Account activation

- **User Profile**
  - Complete profile setup
  - Personal information management
  - Update contact details
  - Address information

## Technology Stack

- **Backend**: Flask (Python)
- **Database**: MySQL
- **ORM**: SQLAlchemy
- **Authentication**: Flask-Login
- **Forms**: Flask-WTF, WTForms
- **Email**: Flask-Mail
- **Security**: Flask-Bcrypt, itsdangerous
- **Frontend**: Bootstrap 5, HTML/CSS, JavaScript
- **Rate Limiting**: Flask-Limiter

## Installation

1. Clone the repository: