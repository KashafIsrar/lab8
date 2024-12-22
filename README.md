# lab8
# ShadowForge Fitness Website

Welcome to the **ShadowForge Fitness** website repository! This is a fitness gym website developed using Flask for the backend and HTML/CSS for the frontend. The site provides information about the gym's services, membership options, and contact details.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)

## Project Overview

ShadowForge Fitness is a web-based application that highlights the offerings of a premium gym in Karachi. The site includes sections such as:
- A welcoming hero section with a call-to-action.
- Detailed information about the gym's mission and services.
- Easy-to-navigate membership and contact pages.

## Features

- **Responsive Design**: Mobile-first design ensures compatibility across all devices.
- **Dynamic Routing**: Flask-powered routes for smooth navigation.
- **Service Details**: Overview of the services offered by the gym.
- **Contact Information**: Easily accessible contact details.

## Technologies Used

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3
- **Static Assets**: Images and styles managed in Flask's `static` folder
- **Template Engine**: Jinja2

## Getting Started

### Prerequisites

- Python 3.x
- Flask library

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shadowforge-fitness.git
   cd shadowforge-fitness
   ```

2. Install dependencies:
   ```bash
   pip install flask
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Access the website in your browser at:
   ```
   http://127.0.0.1:5000/
   ```

## Folder Structure

```
shadowforge-fitness/
│
├── static/
│   ├── css/
│   │   └── styles.css
│   ├── img/
│   │   ├── logo.png
│   │   ├── aboutimg.jpg
│   │   └── service1.jpg
│
├── templates/
│   ├── index.html
│   ├── about.html
│   └── membership.html
│
├── app.py
└── README.md
```



