# Flask Blog Website

This project is a lightweight web application using Flask and designed for creating and managing blog posts. Admin can create accounts, write, edit, and delete posts.
## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication:** Secure user registration, login, reset password, and profile management.
- **Blog Management:** On the home page, you can view the latest blog posts and can navigate through multiple pages of blog posts using older posts.
- **Interaction:** Authenticated users can add, update, and remove blog posts.
- **Responsive Design:** Mobile-friendly UI ensuring a consistent experience across devices.

## Technologies Used

- **Flask:** Python-based web framework for backend development.
- **HTML/CSS/JavaScript:** Frontend development for a responsive and interactive UI.
- **Bootstrap:** Frontend framework for responsive design and UI components.
- **Jinga2:** Web template engine that extensively helps to write Python code within the HTML file.

## Setup Instructions

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone git@github.com:ydvprbn/flask-blog-project.git
   cd flask-blog-project
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   ```
3. **Activate the virtual environment:**

   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **To run the project:**

   ```bash
   python main.py
   ```

6. **Open your web browser and navigate to:** 
   ```bash
   http://127.0.0.1:8000/
   ```

## Contributing

I welcome contributions from the developer community to help improve and grow the Flask Blog project. Whether you're interested in fixing bugs, adding new features, improving documentation, or enhancing the user experience, your contributions are highly valuable.

## License

This project is licensed under the [MIT License](LICENSE).
