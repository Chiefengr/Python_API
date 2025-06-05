# Basic Flask User API

This project demonstrates a simple RESTful API built with **Flask**, providing basic functionalities for retrieving user information and creating new user entries. It's a foundational example for understanding web APIs in Python.

---

## Features

* **Home Route (`/`):** A simple welcome message to confirm the API is running.
* **Get User (`/get.user/<user_id>`):** Retrieves mock user data based on a provided `user_id`.
    * Supports an optional `extra` query parameter to include additional data in the response.
* **Create User (`/create-user`):** Accepts `POST` requests with JSON data to simulate the creation of a new user. Returns the received data.

---

## Technologies Used

* **Python 3.x**
* **Flask**: A lightweight Python web framework.

---

## Setup and Installation

Follow these steps to get the project up and running on your local machine.

### Prerequisites

Ensure you have **Python 3** installed on your system.

### Steps

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```
    (Remember to replace `your-username/your-repo-name` with your actual GitHub details).

2.  **Create and activate a virtual environment (recommended):**
    Virtual environments help manage project dependencies without conflicts.
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On macOS/Linux
    # venv\Scripts\activate   # On Windows
    ```

3.  **Install dependencies:**
    Flask is the only dependency.
    ```bash
    pip install Flask
    ```

---

## Usage

Once installed, you can run the Flask application and interact with its API endpoints.

### Running the Application

From your project's root directory (where `app.py` is located) and with your virtual environment activated:

```bash
python app.py
