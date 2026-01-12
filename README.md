📝 Blog Website (Python + Flask)

A simple Blog Web Application built using Python and Flask, designed to demonstrate backend fundamentals, templating, and deployment readiness using Docker.

This project is suitable for learning, portfolio showcase, and basic production deployment.

🚀 Features

Create and manage blog posts

Server-side rendering using HTML templates

Form handling for user input

Clean project structure with static assets

Docker support for easy deployment

Production-ready configuration (Procfile)

🛠 Tech Stack

Python

Flask

HTML / CSS

Jinja2 Templates

Docker

Gunicorn

Git & GitHub

📂 Project Structure
blog-for-deployment/
│
├── app.py              # Main Flask application
├── forms.py            # Form definitions
├── templates/          # HTML templates
├── static/             # CSS & static assets
├── requirements.txt    # Python dependencies
├── runtime.txt         # Python runtime version
├── Dockerfile          # Docker configuration
├── Procfile            # Deployment process file
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/ranjeet-verse/blog-for-deployment.git
cd blog-for-deployment

2️⃣ Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the application
python app.py


The app will be available at:

http://localhost:5000

🐳 Run with Docker
docker build -t flask-blog .
docker run -p 5000:5000 flask-blog

📦 Deployment

This project is deployment-ready and can be deployed using:

Docker

Heroku / Railway / Render

Any platform supporting Procfile

📌 Future Improvements

User authentication (login & register)

Database integration (PostgreSQL / SQLite)

REST API version using FastAPI

Blog comments & likes

Admin dashboard

👤 Author

Ranjeet Bhosale

LinkedIn: https://linkedin.com/in/ranjeet-bhosale-86b254335

