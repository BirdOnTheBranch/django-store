&nbsp;
# django-store

*Shop online. It can create coupons to manage discounts or promotions. it use Celery and Rabbitmq to create and send the bills by email(also pdf format). The app contains translate system whit rosetta and it can manage payments with Braintree.*

&nbsp;
###### Hi, human. The repo uses:
 
```
Django==3.0.9
Pillow==7.2.0
celery==4.4.7
braintree==4.3.0
WeasyPrint==51
django-rosetta==0.9.4
```

&nbsp;
###### To run:

Its necessary install [Erlang](https://computingforgeeks.com/how-to-install-latest-erlang-on-ubuntu-linux/) in ubuntu to run celery and [Rabbitmq](https://computingforgeeks.com/how-to-install-latest-rabbitmq-server-on-ubuntu-linux/) to manage client.
You can create a [Braintree](https://www.braintreepayments.com/es/sandbox) account if you want to integrate payments.


In store/
  
```
python manage.py collectstatic
pip install -r requirements.txt 
python manage.py runserver 0.0.0.0:8000
```
And use django admin to manage the app.

&nbsp;
###### License:
This project is licensed under the MIT License - see the [LICENSE](https://github.com/BirdOnTheBranch/django-store/blob/master/LICENSE) file for details

&nbsp;
###### Any questions or nice talk: [@wane_emece](https://twitter.com/WaneEmece).