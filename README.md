# WebBasedOnDjango

django==2.1.5
Python==3.7.5

After cloning the code from github to your workplace, go to the Anaconda Prompt (Anaconda) and enter the following code in order,
C:\Users\*****\tango_with_django_project requires replacing the path where you store your code with.

    conda activate rango     

    pip install -r requirements.txt

    cd C:\Users\*****\tango_with_django_project

    python manage.py makemigrations rango

    python manage.py migrate

    python population_script.py

    python manage.py runserver 127.0.0.1:5555

    open http://127.0.0.1:5555/
