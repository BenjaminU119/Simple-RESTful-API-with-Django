Simple RESTful API with Django
==============================

This is the source code for howCode's simple RESTful API with Django.

You can watch the video that accompanies this source code here: https://youtu.be/BSHRftLtPEg

* Run server:
``` shell
  python manage.py runserver
```

* Get：
``` http  
http://localhost:8000/$car_name  # car_name as laosilaisi, dazon, baoma, benci
```

* Post: from postman
``` shell
curl --location --request POST 'http://localhost:8000/car' \
--header 'Content-Type: text/plain' \
--data-raw '{
    "car_name":"dazon",
    "top_speed":89
}'
```

