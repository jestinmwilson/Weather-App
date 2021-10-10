# Weather-App


https://user-images.githubusercontent.com/80836634/136693353-4d6f1510-07bd-48bb-97ed-cedff9dc5b21.mp4


![w1](https://user-images.githubusercontent.com/80836634/136693380-8b280950-7b5e-470a-9de4-255d3f0aa314.png)





How to run this project :

1- Download/clone the entire project and open it in IDE

    https://github.com/jestinmwilson/Weather-App.git
 
2- install the virtual environment

    py -m pip install --user virtualenv

3- create virtual environment
   
    py  -m venv env
   
4- activate the virtual environment
        
    .\env\Scripts\activate
    
5- Install requirements
   
    pip install -r requirements.txt

6- migrate 
   
    python manage.py migrate
    python manage.py makemigrations
7- runserver

    python manage.py runserver

8- For Admin Login
    
    python manage.py createsuperuser
