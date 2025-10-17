# Flask Blog Application

A clean and modern blog application built with Flask, featuring a rich text editor and Bootstrap styling.

## Features

- 📝 Create, edit, and delete blog posts
- 🎨 Rich text editor with CKEditor
- 📱 Responsive Bootstrap design
- 🗄️ SQLite database for data persistence
- 🔍 Clean and intuitive user interface

## Technologies Used

- **Flask** - Web framework
- **SQLAlchemy** - Database ORM
- **Bootstrap-Flask** - UI styling
- **Flask-CKEditor** - Rich text editing
- **Flask-WTF** - Form handling
- **SQLite** - Database

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Py-Day67
```

2. Install the required packages:

**On Windows:**
```bash
python -m pip install -r requirements.txt
```

**On macOS/Linux:**
```bash
pip3 install -r requirements.txt
```

## Running the Application

1. Start the Flask development server:
```bash
python main.py
```

2. Open your web browser and navigate to:
```
http://localhost:5002
```

## Usage

- **Home Page**: View all blog posts
- **Create Post**: Click "Create New Post" to add a new blog entry
- **Edit Post**: Click "Edit Post" on any post to modify it
- **Delete Post**: Click the "✘" symbol next to any post to delete it
- **About/Contact**: Static pages accessible via navigation

## Project Structure

```
Py-Day67/
├── main.py                 # Main Flask application
├── requirements.txt        # Python dependencies
├── instance/
│   └── posts.db           # SQLite database (auto-created)
├── templates/
│   ├── header.html        # Header template
│   ├── footer.html        # Footer template
│   ├── index.html         # Home page
│   ├── post.html          # Individual post view
│   ├── make-post.html     # Create/edit post form
│   ├── about.html         # About page
│   └── contact.html       # Contact page
└── static/
    ├── css/
    │   └── styles.css     # Custom styles
    ├── js/
    │   └── scripts.js     # JavaScript
    └── assets/
        ├── favicon.ico
        └── img/           # Background images
```

## Development

The application runs in debug mode by default. Any changes to the code will automatically restart the server.

To stop the server, press `Ctrl+C` in your terminal.

## Database

The application uses SQLite database that is automatically created in the `instance/posts.db` file when you first run the application.
