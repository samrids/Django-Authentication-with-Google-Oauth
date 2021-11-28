1. Create a new virtual environment 
2. Activate virtual environment 
3. Clone git with command 
   git clone https://github.com/samrids/Django-Authentication-with-Google-Oauth.git
4. Install requirements library
   pip install -r requirements.txt
5. Create and configure a new Google APIs project
Head over to Google Developer APIs Console and create a new project.
Link:
https://console.cloud.google.com/apis/dashboard

6. Create super user
7. Runserver 
Open http://127.0.0.1:8000/admin and login to Django Admin. Under Sites click Add and put 127.0.0.1:8000 as both the Domain name and Display name.

8. Add a social app in Django admin
Provider: Google
Name: OAuth App
Client id: <The client ID you created in step 4>
Secret key: <The Secret key you created in step 4>
Sites: 127.0.0.1:8000