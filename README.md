# web-store-data-scraping-and-recommendation-system-development-with-django

A comprehensive Django project that leverages web scraping to extract data from an e-commerce platform, paired with a recommendation system to deliver customized product suggestions. Users can access personalized recommendations by logging into the system, where their preferences are taken into account. This project illustrates how Django can be effectively combined with machine learning techniques to elevate the user experience in e-commerce.

To test it on your computer, follow the steps below:

**1.** Clone the repo

```bash
git clone https://github.com/rrumark/data-scraping-and-recommendation-system.git
```
**2.** Go into the project
```bash
cd data-scraping-and-recommendation-system
```
**3.** Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # Linux or macOS
# venv\Scripts\activate  # Windows
```
**4.** Install required packages
```bash
pip install -r requirements.txt
```
**5.** Apply database migrations and run the server

```bash
python manage.py migrate
python manage.py runserver
```
**6.** Load product data

```bash
python manage.py loaddata fixtures/products_data.json
```
**7.** Run the server again

```bash
python manage.py runserver
```
