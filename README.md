# Blog Project

A Django-based web application for creating, managing, and viewing blog posts.

## Features

- User authentication (sign up, login, logout)
- Create, edit, and delete blog posts
- View a list of all blog posts
- View individual blog post details
- Comment on blog posts
- Responsive design for mobile and desktop

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd blog_project
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. Run the development server:
    ```bash
    python manage.py runserver
    ```

6. Open your browser and navigate to `http://127.0.0.1:8000`.

## Usage

- Register for an account or log in with an existing account.
- Create new blog posts from the dashboard.
- Browse and comment on blog posts.

## Folder Structure

```
blog_project/
├── blog/               # Main app for blog functionality
├── users/              # App for user authentication
├── static/             # Static files (CSS, JS, images)
├── templates/          # HTML templates
├── manage.py           # Django management script
└── README.md           # Project documentation
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.