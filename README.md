# 📊 Pollapp
![image](https://github.com/user-attachments/assets/48982808-9e55-4ebd-9a39-93c46b765dfd)


## Distinctiveness and Complexity:
This project was very challanging for me. For the first time, I created a project completely from scratch and by myself.
When creating Pollapp, I used almost everything I learned during the course, and even more. 
In the project, in addition to the previously known python, django, javascript, html, css, I also used: Django REST framework which helped me create an API, Bulma which helped me make the website look good and Chart.js which helped me make graphs for polls

## What’s contained in each file:

#### - views.py: all the backend logic behind rendering templates
#### - urls.py: all the paths on the website
#### - serializers.py: converting database results to json responce
#### - models.py: is where all the sql django models are
#### - templates folder : there are all the html files that Pollapp uses
#### - static folder : there are all the .js and .css and images files that are use within Pollapp
#### - Rest of the files are just basic, unchanged django files that are create while starting django project

## How to run Pollapp on your device

#### 1. Clone Pollapp github repository
#### 2. Run docker `docker build . -t pollapp:latest`
#### 3. Next run `docker run -p 8000:8000 pollapp:latest`
#### 4. Open your browser and go to "localhost:8000" and you sould be able to use Pollapp
##### There is already one superuser created, you can use it if you want - Username: cs50  Password: cs50

## Tools used while creating Pollapp

#### - Python | Used as backend programming language
#### - Django | Python based framework I used to create backend for Pollapp
###### -     Django REST framework | Used to create Pollapp API's 
#### - Javascript | Used to create frontend features
###### -     Charts.js | Used to create pie charts of number of votes each option had in poll
#### - HTML | Standard markup language for Web pages
#### - CSS | Used to style HTML
###### -     Bulma | Used to make frontend design look good
###### -     Fontawesome | Used to get access to many icons


## How to use Pollapp

#### 1. Create new account by clicking Register button (you can also login with already created superuser profile)
#### 2. Go to "Polls" and click on "Create" button in order to create new poll
#### 3. You can enter Question, Ansewrs  (minimum 2 and maximum 10) and specify if you want your poll to be public or not (public- users will be able to see it on "polls" page, private - only users with link will be able to see it)
#### 4. Send poll link to your friends to vote and like (they need to be logged in to vote and like)
#### 5. If you dont want your poll to be active you can deactivate it by clicking in "Deactivate" button
#### 6. By clicking on "Profile' you can see your Active, Liked and Deactivated polls

## How to use Pollapp API's

#### 1. Go to "/api/all" for information about all public and active polls on Pollapp
#### 1. Go to "/api/poll/{url code}" for information about specific poll. You can also access private and disactivated polls if you have their url codes
###### You can find url codes after "/poll/" while visiting poll page.
###### Example: when you visit "/poll/foo" your url code is "foo"
###### You can use Pollapp API's even if you are not logged in 



