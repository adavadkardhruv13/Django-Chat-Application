# Django-Chat-Application

## Overview

This is a simple chat application built using Django. Users can create chat rooms, join existing rooms, and exchange messages within those rooms.

## Features

- **Room Creation:** Users can create new chat rooms.

- **Room Joining:** Users can join existing chat rooms.

- **Real-Time Messaging:** Messages are updated in real-time using AJAX.

## Prerequisites

- Python 3.x
- Django 3.x

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/django-chat-app.git
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd django-chat-app
    ```

3. **Create a Virtual Environment:**
    ```bash
    python3 -m venv venv
    ```

4. **Activate the Virtual Environment:**
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

5. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

6. **Apply Database Migrations:**
    ```bash
    python manage.py migrate
    ```

7. **Run the Development Server:**
    ```bash
    python manage.py runserver
    ```

8. **Visit the Application:**
    Open your web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to access the chat application.

## Usage

- Visit the home page and create a new chat room or join an existing one.

- Start chatting by sending messages in the room.

## Contributing

Contributions are welcome! Please follow the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
