
## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the backend lessons.

Welcome varsha2316,
Electronics Ecommerse
A portal to connect to buy / sell electronics online, sellers can sell, users can browse and buy electronics online.

UX - Requirements
Wire Frame and UX design
()

# Features

## Existing Features - User Stories
User stories:
1.	As a User, I should be able to view products details on the website
2.	As a User, I should be able to search products by name using the search textbox on the home page
3.	As a User, I should be able to search products by description using the search textbox on the home page
4.	As a User, I should be able to arrange the search results based on category (A-Z)
5.	As a User, I should be able to arrange the search results based on category (Z-A)
6.	As a User, I should be able to arrange the search results based on review ratings  (high to low)
7.	As a User, I should be able to arrange the search results based on review ratings  (low to high)
8.	As a User, I should be able to arrange the search results based on cost (high to low)
9.	As a User, I should be able to arrange the search results based on cost (high to low)
10.	As a User, I should be able to arrange the search results based on name (A-Z)
11.	As a User, I should be able to arrange the search results based on name (Z-A)
12.	As a User, I should be able to add items to shopping bag without login
13.	As a User, I should be able to add items to shopping bag with login
14.	As a User, I should be able to register to the website
15.	As a User, I should be able to login to the website
16.	As a User, I should be able to create my profile
17. As a User, I should be able to manage (edit) products
18. As a User, I should be able to remove products
19. As a User, I should be able to add more than 1 product to shopping bag
20. As a User, I should be able to remove product to shopping bag
21. As a super user be able to manage (edit) products from website
22. As a super user be able to remove products from website


## Features Left to Implement
compete stripe payment


## Technologies Used

The project used BootStrap theme to have reusable CSS styling and make the site responsive.
Icons / Images were taken from Font-Awesome website
Styling was taken from Google fonts
Used Python for business logic implementatin
django framework to speedup development and use standaized features like allauth
SQL lite for DB
asgiref==3.2.10
dj-database-url==0.5.0
Django==3.1.1
django-allauth==0.42.0
django-countries - to A country field for Django models that provides all ISO 3166-1 countries as choices
django-crispy-forms - to have DRY Django forms
gunicorn -  a Python WSGI HTTP Server for UNIX
oauthlib - OAuthLib is a framework which implements the logic of OAuth1 or OAuth2 without assuming a specific HTTP request object or web framework.
Python Imaging Library -  support for opening, manipulating, and saving many different image file formats. 
psycopg2-binary, python3-openid -  Python packages to support use of the OpenID decentralized identity system in your application, update to Python 3.
pytz -This library allows accurate and cross platform timezone calculations
requests-oauthlib -  libraries to provide an easy-to-use Python interface for building OAuth1 and OAuth2 clients.
sqlparse - It provides support for parsing, splitting and formatting SQL statements.
stripe - The Stripe Python library provides convenient access to the Stripe API from applications written in the Python language. 
whitenoise -It's designed to work with a CDN for high-traffic sites so you don't have to sacrifice performance to benefit from simplicity.

## Testing


# Manual Testing -Test senarios
Testing has been performed to verify and validate the software as per the requirements. Manual Testing performed for the below
1.	Test to check if user Able to view products details on the website
2.	Test to check if user Able to search products by name using the search textbox on the home page
3.	Test to check if user Able to search products by description using the search textbox on the home page
4.	Test to check if user Able to arrange the search results based on category (A-Z)
5.	Test to check if user Able to arrange the search results based on category (Z-A)
6.	Test to check if user Able to arrange the search results based on review ratings  (high to low)
7.	Test to check if user Able to arrange the search results based on review ratings  (low to high)
8.	Test to check if user Able to arrange the search results based on cost (high to low)
9.	Test to check if user Able to arrange the search results based on cost (high to low)
10.	Test to check if user Able to arrange the search results based on name (A-Z)
11.	Test to check if user Able to arrange the search results based on name (Z-A)
12.	Test to check if user Able to add items to shopping bag without login
13.	Test to check if user Able to add items to shopping bag with login
14.	Test to check if user Able to register to the website
15.	Test to check if user Able to login to the website
16.	Test to check if user Able to create my profile
16.	Test to check, user be able to create my profile
17. Test to check, super user be able to manage (edit) products from website
18. Test to check, super user be able to remove products from website
19. Test to check, super user be able  add more than 1 product to website
20. Test to check, user able to add product to shopping bag
21. Test to check, user able to remove product to shopping bag



## How your project looks and works on different browsers and screen sizes
The website is designed with bootstrap and is tested for responsiveness on Desktop / Laptop /Tablet /Mobile View.


It has been tested for iphone6/7/8 , also in iPad.
Any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.


Deployment to heroku



![Heroku URL] (https://varsha-ecommerse.herokuapp.com/)

Credits
Bootstrap theme taken from
(https://getbootstrap.com/docs/4.4/getting-started/introduction/#starter-template)


