# Servlet_JSP_Applications

This repository contains a simple frontend demo (single-page HTML) that illustrates three parts commonly used with Servlet/JSP projects:

- Part A: User Login (client-side demo)
- Part B: Employee Records (static data table)
- Part C: Student Attendance (client-side attendance storage)

## Usage

1. Download or clone this repository.
2. Open `index.html` in your browser to view the demo.
3. To host on GitHub Pages:
   - Create a new repository on GitHub.
   - Commit and push these files.
   - In repository Settings -> Pages, set the source to the `main` branch and `/ (root)` folder.
   - After a minute, your site will be available at `https://<username>.github.io/<repo-name>/`

## Notes for integration with Servlet/JSP backend

This is a static frontend demo. To integrate with a Java backend:
- Replace client-side arrays and form handlers with AJAX/fetch calls to your servlet endpoints.
- Use JDBC inside servlets to fetch/store real employee and attendance data.
- Protect credentials — do **not** hardcode in production.

