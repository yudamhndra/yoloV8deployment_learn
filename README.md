# Flask Project

This is a Flask web application. Follow the steps below to set up and run the project on your local machine.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.7 or higher.
- You have installed Git.
- You have a working internet connection.

## Installation

### 1. Clone the Repository

Use Git to clone the repository to your local machine:

```bash
git clone https://github.com/yudamhndra/yoloV8deployment_learn.git
cd yoloV8deployment_learn
```

### 2. Create a Virtual Environment

Create a virtual environment to manage dependencies:

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

Activate the virtual environment.

For Windows:

```bash
venv\Scripts\activate
```

For macOS and Linux:

```bash
source venv/bin/activate
```

### 4. Install Dependencies

Install the necessary dependencies using `pip`:

```bash
pip install -r requirements.txt
```

### 7. Run the Application

Start the Flask application:

```bash
python yolo_app.py
```

You should see output indicating that the server is running and accessible at `http://127.0.0.1:5000`.

## Usage

To use the application, open your web browser and navigate to `http://127.0.0.1:5000`.

## Updating Dependencies

If you add new dependencies, update the `requirements.txt` file:

```bash
pip freeze > requirements.txt
```

## Adding Virtual Environment to `.gitignore`

To avoid committing the virtual environment, add it to your `.gitignore` file. Open `.gitignore` and add the following line:

```plaintext
venv/
```

## Contributing

To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Create a pull request.

## Source
https://www.youtube.com/watch?v=rapWRxOYYUw
