# Flask Jinja2 Conditionals

A beginner-friendly Flask project demonstrating how to use **Jinja2 conditional statements** (`if`, `else`) to display dynamic content based on data passed from a Flask application.

## Features

* Flask application setup
* Template rendering using `render_template()`
* Passing variables from Python to HTML
* Jinja2 `if-else` conditional statements
* Dynamic webpage content

## Technologies Used

* Python 3
* Flask
* HTML5
* Jinja2

## Project Structure

```text
project/
│
├── app.py
└── templates/
    └── index.html
```

## How It Works

* The Flask application passes an `age` variable to the HTML template.
* The Jinja2 template checks whether the age is **18 or older**.
* If the condition is true, the page displays:

```
You can vote.
```

* Otherwise, it displays:

```
You cannot vote. Please wait until you are 18.
```

## Run the Project

1. Install Flask

```bash
pip install flask
```

2. Start the application

```bash
python app.py
```

3. Open your browser

```
http://127.0.0.1:5000/
```

## Learning Objectives

This project helps beginners understand:

* Flask routing
* `render_template()`
* Passing variables to templates
* Jinja2 template syntax
* Conditional rendering with `if` and `else`
