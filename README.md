#activer l'environnement virtuel
source/bin/venv/activate
source/Scripts/activate

#installer django
pip  install django

#install admin interface
pip install django-admin-interface


INSTALLED_APPS  =  ( 
    # ... 
    'admin_interface' , 
    'flat_responsive' ,  # uniquement si version Django <2.0 
    'à plat' ,  # uniquement si version Django <1.9 
    'colorfield' , 
    # ... 
    'django.contrib.admin' , 
    # ... 
)


#install requirement
pip install -r requirements.txt
