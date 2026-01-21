# php-identity-access-management

## Overview
Identity and access management system built with PHP, focused on secure authentication,
# PHP Identity and Access Management

## Overview
Identity and access management system built with PHP, focused on secure authentication,
session handling, and scalable architecture principles.

## Architecture
The application follows an MVC-inspired architecture to ensure clear separation
between controllers, business logic, data access, and views.

## Security Considerations
- Passwords are hashed using `password_hash`
- Sessions are regenerated after successful login
- Prepared statements are used to prevent SQL injection
- HTTP-only cookies are enforced for session handling
- Access to protected routes is controlled via middleware

## Tech Stack
- PHP
- MySQL
- PDO

## Project Status
** In active development **
session handling, and scalable architecture principles.

