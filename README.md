# My First website with Django.
This blog website is focused heavily on the backend code using django and contains basic frontend using css, html and bootstrap.\
The database is managed by sql and API calls are handled by built in Django features, which can easily be switched out with RESTful API.
I have not made the website live yet, it can still be run on local server using `-python manage.py runserver`\

Here are some features of the blog: 
## Home Page
Home page contains all the blogs posted by all the users sorted by date-time posted. It also has options to **Login** and **Register** at the top right corner(If  you visit the page without logging in).
The sidebar is just a frontend part has no backend utility as of now.
<img width="959" alt="Home_page" src="https://user-images.githubusercontent.com/78678620/133032550-8024abd1-76d0-4906-88cc-1a55f4c35c48.png">

## About Page
Contains more information about the website.
<img width="960" alt="About_page" src="https://user-images.githubusercontent.com/78678620/133034223-14415c06-475f-4381-9f11-29335c7fb716.png">

## Sign Up Page 
Django uses sql for database management. The sign up page authenticates unique user names and one account per email. One can sign up using the most basic information.
<img width="960" alt="Registration_page" src="https://user-images.githubusercontent.com/78678620/133034475-042d59c9-cc10-41e6-a37e-b5788163f01a.png">

## Login In Page
After signing up, one can login in to their new account. This page authenticates username and passwords. Also supports **Reset Password**.
<img width="959" alt="Login_page" src="https://user-images.githubusercontent.com/78678620/133035351-9bc97f4f-1475-49d9-b840-3fcd57075bc4.png">

## User Profile Page
New account gets a default profile picture, but using the profile update page one can update any information(It is also supported by authentication).\
This page can be accessed after login at the top right corner along with **New Post** and **Logout**
<img width="960" alt="Profile_page" src="https://user-images.githubusercontent.com/78678620/133035965-dd108d69-a2fd-4664-9d8e-cd7819c7dd15.png">

## New Blog Post Page
You can write a basic blog and post it on the website. This is also managed by the sqlite database.
<img width="959" alt="Blog_page" src="https://user-images.githubusercontent.com/78678620/133036438-d33a3374-fa23-4fbb-983e-4daddc1f0ea9.png">


## Edit Post Page
If you want to update a blog post or delete it, You can simply click on any of your posts and you can the see the options to do it. 
<img width="960" alt="Edit_Post" src="https://user-images.githubusercontent.com/78678620/133037506-8c24a2b6-46c2-49f9-9a2c-c557e6c51fbb.png">

## Filters on Home Page
Clicking on any user name on the home page will show specifically all their posts made to the current date-time. 
<img width="959" alt="Filter_page" src="https://user-images.githubusercontent.com/78678620/133038039-446e7f83-1aa8-47c3-8ee3-719d2a6b520d.png">

These were few of the main features of my blog. Hope you enjoyed it✌

