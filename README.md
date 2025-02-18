# Price Surfer

## Introduction

Price Surfer is a Django-based web application that aggregates and compares product prices from multiple e-commerce platforms. The platform dynamically fetches product details, including images and prices, when a user searches for a product. This enables users to make informed purchasing decisions by comparing prices from different sources.

🚀 **Features**
- Web Scraping using Selenium to extract product details from Amazon and Flipkart.
- Dynamic search functionality to fetch real-time price data.
- Simple and intuitive UI for seamless navigation.

🛠 **Technologies Used**
- **Backend**: Django, Python
- **Frontend**: HTML, CSS, JavaScript
- **Web Scraping**: Selenium

📝 **Installation Steps**

### Prerequisites
Ensure you have the following installed:
- Python (>=3.8)
- Django
- Selenium
- ChromeDriver (compatible with your Chrome version)

### Steps to Run the Project

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Kolli-VenkataRushita/Price-Surfer.git
   ```
2. **Navigate to the Project Directory**:
   ```sh
   cd Price-Surfer
   ```
3. **Create and Activate a Virtual Environment**:
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```
4. **Install Dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
5. **Set Up Selenium**:
   - Download and install ChromeDriver compatible with your Chrome version.
   - Ensure ChromeDriver is in the system path or specify the path in your Selenium script.
6. **Run the Server**:
   ```sh
   python manage.py runserver
   ```
7. **Access the Application**:
   Open `http://127.0.0.1:8000/` in your browser.

📁 **Folder Structure**
```
Price-Surfer/
├── ourApp/
│   ├── __pycache__/
│   ├── migrations/
│   ├── static/
│   │   ├── css/
│   │   │   ├── images/
│   │   │   ├── styles.css
│   ├── templates/
│   ├── __init__.py
│   ├── admin.py
│   ├── amazon.py
│   ├── apps.py
│   ├── flipkart.py
│   ├── models.py
│   ├── scraper.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── staticfiles/
│   ├── admin/
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
```

