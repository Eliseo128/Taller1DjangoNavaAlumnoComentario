## Taller de DJANGO Desde Cero

procedimiento de instalacion [Mi bestiario en github](https://pages.github.com/).
crear aplicacion  --> django-admin startproject  p_cbtis .
- Min. 21:21  funcionando el cohete  --> python manage.py runserver
- Min. 24:57  crear aplicacion --> python manage.py startapp cbtis_app
- Min. 26:58  en setting registramos la aplicacion cbtis_app
## crear las carpetas templates y static en el directorio cbtis_app
### instalar complemento visualizador de sqlite3 en vs code
- Min. 27:41  realizar migracion --> python manage.py migrate
- configurar urls.py de p_cbtis rutas
```
from django.contrib import admin
from django.urls import path,include

urlpatterns = [
    path('admin/', admin.site.urls),
    path('',include('app1.urls')),
]
```
- creamos urls.py en cbtis_app
```
from django.urls import path
from app1 import views

urlpatterns = [
   path('',views.indexvista, name='indexvista'),
]
```
- Min. 36:08  creamos el archivo index.html en carpeta templates
- Min. 21:21  funcionando el cohete
- Min. 21:21  funcionando el cohete
- Min. 21:21  funcionando el cohete
- Min. 21:21  funcionando el cohete
- Min. 21:21  funcionando el cohete
- Min. 21:21  funcionando el cohete

