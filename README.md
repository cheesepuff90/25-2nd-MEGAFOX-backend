# MEGAFOX

The **MEGAFOX Project** is a movie booking web platform inspired by the MEGABOX service. It was developed by a five-member team to provide features such as movie browsing, theater listings, booking, reviews, and social interactions.

## Project Overview

This project replicates the core workflows of a cinema booking system, enabling users to explore movies, reserve tickets, and share their experiences. It was designed to give the team experience building a scalable backend with real-time booking logic and a smooth user interface.

## Tech Stack

- **Backend:** Python 3.8, Django 3.2, MySQL 8.0  
- **Frontend:** HTML, CSS, JavaScript  
- **Deployment:** AWS EC2, RDS, Load Balancer  

## Agile Methodology

The project followed Agile development practices, with backend and frontend tasks divided among team members and progress tracked through regular sprint reviews.

## ERD
![](https://media.vlpt.us/images/thisisemptyyy/post/c7aa7927-2537-4b1d-8c7e-0385301be90f/megafox_20211030_233447.png)  

## Demo
https://user-images.githubusercontent.com/73053147/139662421-ce2e5b56-0a9b-451e-861a-84021e20f429.mov   

## Features

- Kakao social login integration  
- User authentication and profile management  
- Movie listing and detailed information pages  
- Theater listing with filtering by location  
- Booking system: reservation, confirmation, and history tracking  
- Review management: create, update, delete, and view reviews  
- Likes for movies, theaters, and reviews  

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd megafox

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
    source venv/bin/activate   # Mac/Linux
    venv\Scripts\activate      # Windows


3. Install dependencies:
    ```bash
    pip install -r requirements.txt

4. Configure the MySQL database in your Django settings file and run migrations:
   ```bash
   python manage.py migrate


5. Start the development server:
   ```bash
   python manage.py runserver

6. Open your browser and navigate to:
   ```bash
   http://127.0.0.1:8000
