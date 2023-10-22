# educa

This is the code repository for an e-learning application utilizing the Django framework.

## Instructions

The code is organized into directories and it has a `requirements.txt` file that includes all packages required to run the application. These can be installed with the command `pip install -r requirements.txt`.

## About the Project

**educa** serves as my deliberate practice while guiding me through the entire process of developing professional web applications with Django. This application not only covers the most relevant aspects of the framework, but it also shows how to integrate other popular technologies into a Django project.

The code walks through the creation of a real-world application, solving common problems, and implementing best practices, using a step-by-step approach that is easy to follow.

After completing this project, it has given me a good understanding of how Django works and how to build practical, advanced web applications.

## Requirements

This project requires Python 3.10+ and Django 4.1.

## Django Project

This exercise covers a wide range of web app development topics as specified below:

- **eLearning Platform** : An eLearning platform including a CMS

  - Built course models
  - Created and used data fixtures
  - Used model inheritance to create polymorphic Content
  - Created a custom model field to order course contents
  - Implemented authentication views
  - Built a content management system using class-based views and mixins
  - Restricted access using groups and permissions
  - Built formsets to manage course contents
  - Created drag-and-drop functionality to reorder content in-place using JavaScript and Django
  - Used generic mixins from [django-braces](https://github.com/brack3t/django-braces)
  - Implemented public views and student enrolment views
  - Rendered different type of contents and use [django-embed-video](https://github.com/jazzband/django-embed-video)
  - Cached content using the cache framework
  - Used the [Memached](https://memcached.org/) and Redis cache backends
  - Monitored Redis using [django-redisboard](https://github.com/ionelmc/django-redisboard)
  - Built an API using [Django REST Framework](https://www.django-rest-framework.org/)
  - Created serializers for models and custom API views
  - Handled API authentication and permissions
  - Built API viewsets and routers
  - Consumed API using Python [requests](https://github.com/psf/requests)
  - Created a real-time chat server using Django [Channels](https://github.com/django/channels)
  - Implemented a WebSocket consumer/client using Django and JavaScript
  - Used Redis to set up a channel layer
  - Made a WebSocket that is fully-asynchronous
  - Created settings for multiple environments
  - Configured a production environment using [Docker Compose](https://docs.docker.com/compose/) with PostgreSQL, Redis, [Nginx](https://www.nginx.com/), [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) and [Daphne](https://github.com/django/daphne)
  - Served the project securely through HTTPS
  - Used the Django system check framework
  - Built a custom middleware
  - Created custom management commands

#### product list page
![](images/product_list_page.png)

#### product detail page
![](images/product_detail_page.png)

#### cart detail page
![](images/cart_detail_page.png)

#### checkout page
![](images/checkout_page.png)

#### order summary page
![](images/order_summary_page.png)

#### stripe checkout payment form
![](images/stripe_checkout_payment_form.png)

#### success page
![](images/success_page.png)

#### orders admin page
![](images/orders_page.png)

#### pdf invoice
![](images/pdf_invoice.png)
