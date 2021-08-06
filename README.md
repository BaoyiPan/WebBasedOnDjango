# WebBasedOnDjango

django==2.1.5
Python==3.7.5

After cloning the code from github to your workplace, go to the Anaconda Prompt (Anaconda) and enter the following code in order

    git clone https://github.com/Oliver-821/WebBasedOnDjango.git
    
    conda activate rango     

    pip install -r requirements.txt

    cd WebBasedOnDjango

    python manage.py makemigrations rango

    python manage.py migrate

    python populate_rango.py

    python manage.py runserver 

    open http://127.0.0.1:8000/
