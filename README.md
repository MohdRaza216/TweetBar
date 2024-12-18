# TweetBar

TweetBar is a minimalist social media platform built with Django, designed for users to share short messages and connect with others in a simple, intuitive interface.

## Features

- **User Authentication**: Secure login and registration system.
- **Tweet Management**: Post, edit, and delete tweets.
- **Responsive Design**: Optimized for all devices using Bootstrap.

## Technologies Used

- **Backend**: Django
- **Frontend**: HTML, CSS, Bootstrap

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/TweetBar.git
   cd TweetBar
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

6. **Access the application:**
   Open your browser and go to `http://127.0.0.1:8000/`

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
