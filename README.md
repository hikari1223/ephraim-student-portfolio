# Ephraim B. Balbalec Jr. — Student Portfolio

> **AI Tools and Tutorials Acknowledgment:**  
> AI tools and online tutorials were used as learning and development assistance during this project. AI was used to help explain Django concepts, troubleshoot errors, improve code structure, and provide guidance while developing the website. I reviewed, tested, and modified the generated suggestions and remain responsible for understanding how the code works.

## Project Overview

This project is a multi-page student portfolio website developed using **Django**.

The website presents my personal background, skills, interests, projects, and other information as a **Bachelor of Science in Information Systems student at DMMMSU-NLUC**.

The main purpose of this project is to demonstrate my understanding of Django, HTML, CSS, templates, URL routing, static files, and Git version control.

## Student Information

**Name:** Ephraim B. Balbalec Jr.  
**Program:** Bachelor of Science in Information Systems 
**Year Level:** Second Year  
**School:** DMMMSU-NLUC

## Pages

The website contains the following pages:

- **Home** — Introduction and welcome section
- **About** — Personal background and information
- **Skills** — Programming and technical skills
- **Projects** — Projects and activities
- **Gallery** — Images and visual content
- **Contact** — Contact information and message section

## Features

- Django project and application
- Multiple pages
- Named URL patterns
- Individual Django views
- Django template inheritance
- Reusable navigation bar
- Reusable footer
- Django `{% url %}` template tags
- Django `{% include %}` template tags
- Static CSS files
- Static images
- Responsive website design
- Organized project structure
- Git version control
- GitHub repository

## Technologies Used

- **Python**
- **Django**
- **HTML5**
- **CSS3**
- **Git**
- **GitHub**
- **Visual Studio Code**

## Project Structure

The project uses a Django project called `portfolio_site` and a Django application called `portfolio`.

The website uses a shared `base.html` template for the common layout of the pages. Other templates extend this file using Django template inheritance.

The navigation bar and footer are separated into reusable template components and loaded using Django's `{% include %}` tag.

CSS files and images are stored inside the `static` directory so they can be managed separately from the HTML templates.

A simplified structure of the project is:

```text
portfolio_site/
│
├── manage.py
│
├── portfolio_site/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── portfolio/
│   ├── views.py
│   ├── urls.py
│   └── ...
│
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── about.html
│   ├── skills.html
│   ├── projects.html
│   ├── gallery.html
│   └── contact.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── images/
│
└── README.md
```

## How the Website Works

The Django URL configuration connects each URL to a specific view.

For example:

```text
URL → View → Template → Web Page
```

When a user visits a page, Django receives the URL request, finds the matching URL pattern, runs the corresponding view, and then displays the appropriate HTML template.

The `base.html` file provides the common website structure, while individual pages extend it to avoid repeating the same navigation and footer code.

## Installation

### 1. Clone the Repository

Clone the GitHub repository using:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Then enter the project folder:

```bash
cd portfolio_site
```

### 2. Create a Virtual Environment

Create a Python virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Django

Install Django using:

```bash
pip install django
```

### 4. Run Database Migrations

Run:

```bash
python manage.py migrate
```

### 5. Check the Project

Run the Django system check:

```bash
python manage.py check
```

If there are no errors, the project is ready to run.

### 6. Start the Development Server

Run:

```bash
python manage.py runserver
```

Open the address shown in the terminal, normally:

```text
http://127.0.0.1:8000/
```

## Git and GitHub

Git is used to keep track of changes made to the project.

The project can be connected to a GitHub repository so that the source code can be stored online and copied to another computer when needed.

Basic Git commands used for the project include:

```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

## AI Tools and Tutorials

AI tools and tutorials were used as learning assistance during the development of this project.

AI assistance was used for:

- Understanding Django concepts
- Explaining Python and HTML/CSS code
- Troubleshooting Django errors
- Improving website structure and design
- Learning how Django templates work
- Learning Git and GitHub commands
- Reviewing and improving code

The AI-generated suggestions were not accepted blindly. I reviewed, tested, and modified the code while developing the project.

I understand that I am responsible for understanding the code used in this project and for being able to explain how the Django project, URLs, views, templates, static files, and Git workflow work.

## Learning Outcomes

Through this project, I learned how to:

- Create a Django project and application
- Create and connect Django URL patterns
- Create Django views
- Connect views to HTML templates
- Use template inheritance
- Create reusable template components
- Use static CSS and images
- Build a responsive website
- Use Git for version control
- Upload and manage a project using GitHub
- Use AI tools responsibly as a learning aid

## Author

**Ephraim B. Balbalec Jr.**

Bachelor of Science in Information Systems
DMMMSU-NLUC