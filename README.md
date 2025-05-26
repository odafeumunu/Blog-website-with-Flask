# 🚀 Blog Website with Flask ✍️

A modern, feature-rich blog website built with Flask, SQLAlchemy, and a sprinkle of magic ✨.

## 🌟 Description

This project is a comprehensive blog platform allowing users to create, read, update, and delete blog posts. It includes user authentication, commenting functionality, and an admin interface for managing content. Perfect for sharing your thoughts with the world 🌎!

## 🛠️ Installation

Get the project up and running locally with these simple steps:

- ⬇️ **Clone the Repository**:
  ```bash
  git clone https://github.com/odafeumunu/Blog-website-with-Flask.git
  cd Blog-website-with-Flask
  ```

- 🐍 **Create a Virtual Environment**:
  ```bash
  python -m venv venv
  ```

- 激活虚拟环境：
  - **On Windows**:
    ```bash
    venv\Scripts\activate
    ```
  - **On macOS and Linux**:
    ```bash
    source venv/bin/activate
    ```

- 📦 **Install Dependencies**:
  ```bash
  pip install -r requirements.txt
  ```

- ⚙️ **Set Up Environment Variables**:
  - Create a `.env` file in the root directory.
  - Add the following variables:
    ```
    FLASK_KEY=YourSecretKeyHere
    DB_URI=YourDatabaseURIHere  # e.g., "sqlite:///posts.db" or a PostgreSQL URI
    EMAIL_KEY=YourEmailAddress
    PASSWORD_KEY=YourEmailPassword
    ```

- 🚀 **Run the Application**:
  ```bash
  python main.py
  ```
  Open your browser and navigate to `http://127.0.0.1:5000` 🎉.

## 💡 Usage

<details>
<summary>Detailed Usage Instructions</summary>

1.  **Register/Login**:
    - Navigate to the `/register` or `/login` routes to create an account or log in.

2.  **View Posts**:
    - The homepage (`/`) displays all available blog posts.

3.  **Create a New Post (Admin Only)**:
    - Log in as an admin user (user ID 1).
    - Click on "Create New Post" to add a new blog entry.

4.  **Edit/Delete Posts (Admin Only)**:
    - While logged in as admin, you can edit or delete any post directly from the homepage or individual post page.

5.  **Add Comments**:
    - View a post and use the comment form to add your thoughts.

### Example: Creating a Post

1.  Log in as an admin.
2.  Click "Create New Post".
3.  Fill out the form with a title, subtitle, image URL, and content.
4.  Submit the form to publish the post.

### Screenshot: Post View

![Screenshot of a blog post](https://i.imgur.com/your-screenshot.png)
*(Replace with an actual screenshot)*

</details>

## ✨ Features

- ✍️ **Create Posts**: Easily add new blog entries with a rich text editor.
- 🔐 **User Authentication**: Secure registration, login, and logout functionality.
- 💬 **Commenting System**: Engage with readers through post comments.
- 🛡️ **Admin Interface**: Manage posts with admin-only access for editing and deleting.
- 📧 **Contact Form**: Send messages directly through the website.
- 🎨 **Responsive Design**: Looks great on any device.

## 💻 Technologies Used

| Technology    | Link                               |
| :------------ | :--------------------------------- |
| Flask         | [https://flask.palletsprojects.com/](https://flask.palletsprojects.com/) |
| SQLAlchemy    | [https://www.sqlalchemy.org/](https://www.sqlalchemy.org/)         |
| Flask-WTF     | [https://flask-wtf.readthedocs.io/](https://flask-wtf.readthedocs.io/)     |
| Bootstrap     | [https://getbootstrap.com/](https://getbootstrap.com/)           |
| Flask-CKEditor| [https://pypi.org/project/Flask-CKEditor/](https://pypi.org/project/Flask-CKEditor/) |
| gunicorn      | [https://gunicorn.org/](https://gunicorn.org/)      |
| python-dotenv | [https://pypi.org/project/python-dotenv/](https://pypi.org/project/python-dotenv/) |

## 🤝 Contributing

Contributions are welcome! Here’s how to contribute:

- 🍴 **Fork** the repository.
- 🌿 Create a **new branch** for your feature or bug fix.
- ✍️ Make your changes and **commit** them with descriptive messages.
- 🚀 **Push** your changes to your fork.
- 📤 Submit a **pull request** to the main repository.

## 📝 License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author Info

- Name: [Umunu Odafe Peter]
  - GitHub:  [https://github.com/your-github](https://github.com/odafeumunu)

---

[![Python](https://img.shields.io/badge/python-3.6+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-%23000.svg?style=for-the-badge&logo=SQLAlchemy&logoColor=white)](https://www.sqlalchemy.org/)