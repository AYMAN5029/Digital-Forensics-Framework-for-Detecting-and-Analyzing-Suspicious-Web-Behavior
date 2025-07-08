# Digital Forensics Framework for Detecting and Analyzing Suspicious Web Behavior


[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Introduction
This project focuses on detecting phishing URLs using machine learning techniques. It utilizes Django and Django REST Framework to create an API for URL classification. The project includes feature extraction, model training, and deployment for real-time URL classification. Front-end technologies, including HTML, CSS, JavaScript, and Bootstrap, have been employed for designing and developing the UI.

![Genuine](https://github.com/user-attachments/assets/c0a075bf-eab2-455c-a407-bbfca8cbc021)
![Certain Risk](https://github.com/user-attachments/assets/21bcd7dc-1278-404b-8eca-c84bf54e6ba3)
![Phishing](https://github.com/user-attachments/assets/d0c66f22-0305-417d-93f8-bbb11cd6b2e2)

## Features

- Phished URL detection using machine learning algorithms
- Feature extraction based on various URL attributes
- Django framework for API development
- Bootstrap and jQuery for frontend development

## Getting Started

To get started with this project, follow these steps:

### Prerequisites

- Python 3.x
- Django
- Django REST Framework
- Other required dependencies (specified in `requirements.txt`)

### Methodology
![Methodolody](https://github.com/user-attachments/assets/886425b3-52c9-4618-9cf3-e412b888a2e0)

### Installation

- Sequentially execute this code  

   ```bash
  1. git clone https://github.com/AYMAN5029/Digital-Forensics-Framework-for-Detecting-and-Analyzing-Suspicious-Web-Behavior.git
  2. pip install -r requirements.txt
  3. python manage.py migrate
  4. python manage.py runserver
  ```
## Usage
- Visit the homepage to access the URL classification interface.
- Enter a URL in the provided input field.
- Click the "Predict" button to initiate the classification process.
- The system will analyze the URL using the pre-trained Gradient Boosting model.
- The classification result (phished or not phished) will be displayed on the page.

## Accuracy Score
![COmparative Plot](https://github.com/user-attachments/assets/50c7356d-248c-40d4-bd60-a2565f04083a)

## Project Report And IEEE Paper

https://tinyurl.com/fyp-report-ieee-paper

## Acknowledgments
Special thanks to the contributors and open-source projects that provided inspiration, guidance, and tools for this project.
