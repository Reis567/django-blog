# Django Blog Project - Reis567

This is a blog project developed using Django. It allows users to create and publish blog posts, manage categories and tags, and display pages with custom content. The project follows the MVC (Model-View-Controller) architectural pattern and incorporates various Django features and functionalities.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Reis567/django-blog/
```

2. Create a virtual environment and activate it:

```bash
python -m venv myenv
source myenv/bin/activate
```

3. Install the project dependencies:

```bash
pip install -r requirements.txt
```

4. Run database migrations:

```bash
python manage.py migrate
```

5. Create a superuser account:

```bash
python manage.py createsuperuser
```

6. Start the development server:

```bash
python manage.py runserver
```

The blog project should now be up and running locally at `http://localhost:8000/`.

## Usage

1. Access the admin interface:

   - Open your web browser and go to `http://localhost:8000/admin/`.
   - Log in using the superuser credentials created during installation.

2. Manage blog content:

   - Create, edit, and delete blog posts.
   - Manage categories and tags.
   - Create custom pages with desired content.

3. View the blog:

   - Open your web browser and go to `http://localhost:8000/`.
   - Browse the published blog posts, search by keywords, filter by categories and tags, and view individual posts and pages.

## Project Structure

The project follows a standard Django project structure:

- `blog/`: The main Django application directory.
  - `admin.py`: Configuration for the Django admin interface.
  - `apps.py`: Configuration for the blog application.
  - `models.py`: Definition of database models (e.g., Post, Tag, Category, Page).
  - `urls.py`: URL routing configuration for the blog application.
  - `views.py`: View functions and classes that handle requests and generate responses.
- `blog_project/`: The project's configuration directory.
  - `settings.py`: Django project settings and configuration.
  - `urls.py`: Main URL routing configuration for the project.
- `static/`: Directory for static files (CSS, JavaScript, images).
- `templates/`: Directory for HTML templates used by the blog application.
- `utils/`: Directory for utility files and functions.
- `manage.py`: The Django project management script.

## Features

The blog project includes the following features:

- User authentication: Users can create accounts, log in, and log out.
- Blog post management: Users can create, edit, and delete blog posts.
- Category and tag management: Users can assign categories and tags to blog posts.
- Custom page creation: Users can create pages with custom content.
- Search functionality: Users can search for blog posts by keywords.
- Filtering by category and tags: Users can browse blog posts by category or tags.
- Pagination: Blog posts are displayed in pages with a specified number of posts per page.
- Django admin interface: Provides an interface for managing blog content.
- Responsive design: The blog is designed to be responsive and accessible across different devices.

## Dependencies

The blog project has the following dependencies:

- Django (version 3.2 or above)
- Django Summernote (for rich text editing functionality)
- Pillow (for image processing and handling)
- django-axes (for IP-based login throttling)
- psycopg2 (for PostgreSQL database support)

For more details on the dependencies and their versions, refer to the `requirements.txt` file.

## Contributing

Contributions to the blog project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the project's coding style and guidelines.

To contribute to the project, follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix.
3. Implement your changes.
4. Commit and push your changes to your forked repository.
5. Submit a pull request to the main repository.

Please provide a clear description of your changes in the pull request, along with any relevant information or context.

