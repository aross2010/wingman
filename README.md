# WingMan

CMPE 131 Group Project

## Team Members

| name           | SJSU ID   | SJSU Email              | Github                                              |
| -------------- | --------- | ----------------------- | --------------------------------------------------- |
| Jordan Jimenez | 017511767 | jordan.jimenez@sjsu.edu | [Jordan-Jimenez](https://github.com/Jordan-Jimenez) |
| Alex Ross      | 016812393 | alex.ross@sjsu.edu      | [aross2010](https://github.com/aross2010)           |
| Zhirong Chen   | 017274920 | zhirong.chen@sjsu.edu   | [zchen2003](https://github.com/zchen2003)           |
| Lyxa Tang      | 017541901 | lyxa.tang@sjsu.edu      | [lyxa123](https://github.com/lyxa123)               |

## Description

This is a simple Flask application that provides a flight book interface where users can book flights. The application allows users to search for flights by entering the departure and destination cities, as well as the departure date. The application will then display a list of available flights that match the search criteria.

## Prerequisites

To run this application, you will need to have Python installed on your computer. You can download Python from the official website: [python.org](https://www.python.org/).

## Installation Instructions

Follow these steps to set up and run the application:

### 1. Clone the repository to your local machine:

```
git clone https://github.com/aross2010/cmpe131_flask_app.git
```

### 2. Navigate to the project directory:

```
cd cmpe131_flask_app
```

### 3. Create and Activate a Virtual Environment

<details>
<summary><strong>On macOS/Linux</strong></summary>

#### a. Create a virtual environment:

```
python3 -m venv venv
```

#### b. Activate the virtual environment:

```
source venv/bin/activate
```

</details>

<details>
<summary><strong>On Windows</strong></summary>

#### a. Create a virtual environment:

```
python -m venv venv
```

#### b. Activate the virtual environment:

```
venv\Scripts\activate
```

</details>

### 4. Install the required Python packages:

Install the dependencies listed in the requirements.txt file:

```
pip install -r requirements.txt
```

### 5. Set Up the Database

Run the seeds.py script to populate the database with initial data:

```
python seeds.py
```

### 6. Run the application:

Start the Flask application:

```
flask run
```

### 7. View the application.

Open a web browser and go to http://localhost:5000
