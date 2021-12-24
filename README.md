 ## Inspiration
 - https://www.emaillistverify.com/
 - https://neverbounce.com/

## List of features to be developed for v1
### Guest/Unauthenticated users
- [ ] Login
- [ ] Register (with email verification)
- [ ] Reset password

### Authenticated users
- [ ] 2FA
- [ ] Change password
- [ ] Change profile information
- [ ] View profile information

### Email verification
- [ ] Check email 
      - Email reachability, 
      - Syntax validation, 
      - DNS records validation, 
      - Disposable email address (DEA) validation, 
      - SMTP server validation, 
      - Email deliverability, 
      - Mailbox disabled, 
      - Full inbox, 
      - Catch-all address, 
      - Role account validation, 
      - Free email provider check
- [ ] Upload your dirty list for bulk email list cleaning
- [ ] Download a clean list
- [ ] Verify your email list directly in the tool that you use for sending sending newsletters (integrations): Mailchimp, etc.

## Database architecture
To be done after validation of all points in this document

## Navigation

### Main navigation
- Home
- Login
- Register now

### Second navigation
- FAQ
- Contact us
- Terms of Service 
- Privacy Policy

# Use Cases (workflow)
1. A user can create an account with his username, an email address, and a password.
2. A user should receive a verification link after registration by email.
3. A user must be able to validate his account by email.
4. A user must be able to connect with his email and password.
5. A user can enable an account with his username, an email address, and a password.
6. A user must be able Two-factor authentication for his account.
7. A user can view his last login (time and location).
8. The last two passwords can no longer be accepted when changing password.
9. A user must be able to reset his password.
10. A user can verify a single email or a long list of emails.
11. A user can upload CSV, XLS, and TXT files from a storage for bulk email verification.
12. Once a user's list has been verified, he can download the results (clean email list) in CSV or XLSX formats
13. A user can import an email list into their account directly from a third party service such as Mailchimp, Campaign Monitor, etc.
14. A logged in user can view stats from his activities (verified emails, invalid emails, etc.)

# Technos

## Backend
- Laravel + Livewire/Inertia
- Database: MySQL

## Frontend
- Framework CSS : Tailwind CSS

NB: Some points that are too technical (unit tests for work safety, etc.) are deliberately omitted for the simplicity of the document. They will be treated during the execution of the project.
