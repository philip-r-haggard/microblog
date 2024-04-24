# Microblog

Microblog is a simple CRUD web application built with Python and Flask. The goal of this project is to create a minimalistic blog site where users can create, read, update, and delete blog posts.

## Features

- **Create:** Users can create new blog posts by providing a title and content.
- **Read:** Users can view existing blog posts.
- **Update:** Users can edit and update their own blog posts.
- **Delete:** Users can delete their own blog posts.

## Technologies Used

- **Python:** The backend of the application is written in Python.
- **Flask:** Flask is used as the web framework for building the application.
- **SQLite:** SQLite is used as the developmental database to store blog posts.
- **HTML/CSS:** The frontend of the application uses HTML for structure and CSS for styling.
- **Bootstrap:** Bootstrap is used for frontend styling and layout.

## Setup

1. Clone the repository:

    ```
    git clone https://github.com/philip-r-haggard/microblog.git
    ```

2. Navigate to the project directory:

    ```
    cd microblog
    ```

3. Create a virtual environment:

    ```
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

    ```
    venv\Scripts\activate
    ```

    - On macOS and Linux:

    ```
    source venv/bin/activate
    ```

5. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

6. Run the application:

    ```
    flask run
    ```

7. Open your web browser and navigate to [http://localhost:5000](http://localhost:5000) to view the application.

## Usage

- **Home Page:** Upon visiting the site, users will see a list of existing blog posts.
- **Create Post:** Users can create a new post by clicking on the "New Post" button.
- **View Post:** Users can click on a post title to view its content.
- **Edit Post:** Users can edit their own posts by clicking on the "Edit" button.
- **Delete Post:** Users can delete their own posts by clicking on the "Delete" button.
