# New York City Guide - Django Project
Daniel Jackson & Jessica Lotto
# Github names
jackdee0077 & jlotto8
# To start building the project:
Clone this repository to your local computer

# 1. Create a virtual environment
At the root folder of the repository run:
```
python3 -m venv venv
```
Make sure to call your virtual environment "venv"

# 2. Run virtual environment
# On Windows:
Windows Powershell users:
```
venv\Scripts\activate.bat
```
Bash users:
```
source venv/Scripts/activate
```
# On Unix or MacOS:
```
source venv/bin/activate
```
# 3. Install dependencies

pip install django

pip freeze install
```
pip install -r requirements.txt
```
# 4. Run Django
cd into the nyc-guide directory
run the command: python manage.py runserver
And go to `http://localhost:8000`

# To Stop running the server/application

# To exit the virtual environment
run the command: deactivate

# Structure
The structure of the web pages corresponds to the following (along with their URL paths):

Home /

Brooklyn /brooklyn

Beaches /brooklyn/beaches
Brighton Beach /brooklyn/beaches/brighton%20beach
Coney Island /brooklyn/beaches/coney%20island
Manhattan Beach /brooklyn/beaches/manhattan%20beach
Bronx /bronx

Beaches /bronx/beaches
Orchard Beach /bronx/beaches/orchard%20beach
Zoos /bronx/zoos
Bronx Zoo /bronx/zoos/bronx%20zoo
Manhattan /manhattan

Food /manhattan/food

Cheeky Sandwiches /manhattan/food/cheeky%20sandwiches
Katz's Delicatessen /manhattan/food/katz's%20delicatessen
Veselka /manhattan/food/veselka
Parks /manhattan/parks

Central Park /manhattan/parks/central%20park
Riverside Park /manhattan/parks/riverside%20park
The High Line /manhattan/parks/the%20highline
Washington Square Park /manhattan/parks/washington%20square%20park
Queens /queens

Airports /queens/airports
John F Kennedy International Airport /queens/airports/john%20f%20kennedy%20international%20airport
LaGuardia Airport /queens/airports/laguardia%20airport
Beaches /queens/beaches
Rockaway Beaches /queens/beaches/rockaway%20beaches
Staten Island /staten%20island

Beaches /staten%20island/beaches
Cedar Grove Beach /staten%20island/beaches/cedar%20grove%20beach
Midland Beach /staten%20island/beaches/midland%20beach
South Beach /staten%20island/beaches/south%20beach
Wolfe's Pond Beach /staten%20island/beaches/wolfe's%20pond%20beach
Food /staten%20island/food
Lee's Tavern /staten%20island/food/lee's%20tavern
Ralph's Famous Italian Ices /staten%20island/food/ralph's%20famous%20italian%20ices
Royal Crown Bakery /staten%20island/food/royal%20crown%20bakery

# Technical
Project required the implementation of:

Activity page (view and template) rendered at URL <str:borough>/<str:activity>(i.e. list of beaches, parks)
The Venue page (view and template) rendered at URL <str:borough>/<str:activity>/<str:venue> (i.e. details of a venue like Brighton Beach)

# The following are used in this project:

Python data structures such as Lists, Dictionaries and their associated methods
Python Classes and Inheritance
Django URLs to understand how to capture parameters in views
Django Templates