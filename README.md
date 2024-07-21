# Student Enrollment Application

This is a Django application for student enrollment. It includes an AJAX-based registration form, as well as CSV and PDF export functionalities for the enrolled students.

## Features

- AJAX-based form submission for student registration without page refresh
- Export student data to CSV format
- Export student data to PDF format with formatted headers and layout
- Fields: First Name, Last Name, Email, Date of Birth, USN (University Seat Number), Course

## Requirements

- Python 3.x
- Django 3.x or higher
- ReportLab (for PDF generation)

There is no data present in the data
## Setup

### Clone the repository

```bash
git clone https://github.com/bsshreesha2003/Student_Ajax_pdf-csv-generation
cd studentAjax

pip install django reportlab
python manage.py makemigrations
python manage.py migrate
python manage.py runserver


