# GLA University — Library and Digital Resource Management System

This frontend keeps the **same overall multi-page dashboard structure and UI language as the earlier GLA e-Library frontend**, while the role-specific details and workflows are based on the supplied LDRMS project.

## Roles
### Student / Library Member
- Member dashboard
- Book catalogue
- Digital library
- My books & loans
- Reservations
- Library rules
- Profile
- Help desk

### Librarian Staff
- Librarian dashboard
- Issue book
- Return book
- Renew loans
- Circulation desk catalogue
- Member lookup
- Notices
- Staff profile

### Administrator
- Admin dashboard
- Catalogue inventory
- Digital resource management
- Members directory
- Reports & audit
- IAM role verifier
- Notices
- Admin profile

## Demo credentials
- Student: `LIB-2023-0142` / `Member@123`
  - email: `ananya.rao@gla.ac.in`
- Librarian: `STAFF-LIB-042` / `Staff@123`
  - email: `lakshmi.devi@gla.ac.in`
- Admin: `ADMIN-GLA-001` / `Admin@123`
  - email: `admin@gla.ac.in`

## Run
Extract the ZIP and open `index.html`.

This is a frontend prototype. Role routing, filters and buttons are implemented with client-side JavaScript; there is no database/backend.

## Authorization
Student, Librarian and Administrator use separate dashboards and route permissions. A direct attempt to open a protected page outside the active role is redirected to `pages/unauthenticated.html`. This is a client-side frontend demonstration; a real deployment must enforce the same authorization on the backend/API.
