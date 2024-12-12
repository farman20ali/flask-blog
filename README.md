# Description
- a blog made using flask python framework
- login functionality
- user authentication required on actions to perform
- forget password functionality
- handling posts
- friendly dashboard, and 
- database used php mysql
- email sending 
- edit, create and update posts
- pagination 
- jinja templating
- dynamic webpages
- and more can be added
- structured code

# Flask Blog

## Overview
This project is a blog application built using the Flask Python framework. It provides an intuitive and user-friendly platform for managing posts with secure authentication features. The application emphasizes dynamic content rendering, structured code, and ease of use for both developers and users.

---

## Features
- **User Authentication:** Login and registration functionalities with secure password handling.
- **Forget Password:** Users can reset their password via email.
- **Post Management:** Create, edit, update, and delete posts with an interactive dashboard.
- **Pagination:** Efficiently manage and display a large number of posts.
- **Email Integration:** Send emails for password recovery and notifications.
- **Dynamic Webpages:** Jinja templating for dynamic and responsive content rendering.
- **Structured Codebase:** Modular and scalable design for easier maintenance and extension.

---

## Technologies Used
- **Backend Framework:** Flask
- **Frontend:** HTML, CSS, and Jinja2 Templates
- **Database:** MySQL (via PHPMyAdmin)
- **Email Integration:** Flask-Mail

---

## Getting Started

### Prerequisites
- Python 3.8 or later
- MySQL Database
- Flask and required dependencies

### Installation Steps
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd flask_blog
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure database:
   - Create a MySQL database.
   - Update the `config.py` file with database credentials.

4. Run the application:
   ```bash
   flask run
   ```

5. Access the application at `http://127.0.0.1:5000`.

---

## Example Endpoints
### User Authentication
- **Login:** `/login` (POST)
- **Register:** `/register` (POST)
- **Forgot Password:** `/forgot-password` (POST)

### Post Management
- **Create Post:** `/create` (POST)
- **Edit Post:** `/edit/<post_id>` (POST)
- **Delete Post:** `/delete/<post_id>` (POST)

---

## Tags
- `Flask`
- `Python`
- `MySQL`
- `Blog`
- `Authentication`
- `Dynamic Pages`
- `Pagination`
- `Email Integration`

---

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

