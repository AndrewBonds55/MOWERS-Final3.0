# CIDM-6325-Final-Project
Andrew Bonds CIDM 6325 Final Project Repository

| Feature| Description |
| ----------- | ----------- |
| Authentication | The Django Authentication feature will allow users to create secure passwords allowing them to login |
| SEO Otimization | This is a unique quality of Django that will give Mowers an advantage over rivals. The SEO feature will help by submitting Mowers to a search engine so that it shows up in the top results. |
| High Security | The high security feature of Django ensures that all of our customer data will be secure giving both the customers as well as the company a peace of mind |
| Scalability | As Mowers continues to grow the scalabilty feature will allow for the application to be scaled accordingly in instance of rapid development so users are not inconvinienced|
| Speed/App Performance | Because it provides quick development from concepte to completion rapid updates to any issues that the users might find |
| Intuitive UX | Allows for users to navigate through the Mowers App seamlessly and conviniently |

| Feature | Description of Feature |
| ----------- | ----------- |
| Authentication | Django has authentication automatically built into the framework. This will allow users to securely sign in with a strong password and a Multi Factor Authentication method such as the users cell phone or email for added security ('django.contrib.auth') |
| SEO Optimization | The SEO system that Django uses is one of the most beneficial aspects of using Django. With this, users will be able to find Mowers when searching for relevant searchers (class MyMetadata(seo.Metadata):title       = seo.Tag(head=True, max_length=68) description = seo.MetaTag(max_length=155) keywords    = seo.KeywordTag() heading     = seo.Tag(name="h1") |
| Authentication URL's | Allows for users to login,logout, and manage password urlpatterns += [ path('accounts/', include('django.contrib.auth.urls')),]| 
| Security | To enable extra secuirty for your app you can add the following code <input type="hidden" name="csrfmiddlewaretoken" value="0QRWHnYVg776y2l66mcvZqp8alrv4lb8S8lZ4ZJUWGZFA5VHrVfL2mpH29YZ39PW" /> |
| Intuitive UX | Description of Feature |

| Domain Name | The Domain that will be used for Mowers|
| ----------- | ----------- |
| Mowers Domain Name | http://dingdongmowers.com/ |

| Deployment Method | It is planned to deploy mowers with Heroku |
| ----------- | ----------- |
| Planning on usering Heroku for Mowers | Deploying With Heroku allows for the focus to be solely on making mowers great and not having to worry about the server or networking side of the application. With Heroku the server and networking side is built in |



* You must implement *all* **Baseline** components - Gets you to 70% of the value
* You will implement *at least* six **Good** components - Gets you to 80% of the vaue
* You will implement *at least* two **Better** components - Gets you to 85% of the value
* You will implement *at least* two **Best** components - Gets you to 90% of the value

Where is the remaining 10%? It comes from the synthesis and service to your idea (implementation).

* **Baseline**: Essential Django knowledge that must be demonstrated in your final project
* **Good**: Fundamental knowledge that sets up a more useful app
* **Better**: Approaching a higher degree of robustness
* **Best**: Approaching professional-grade features and tools

Topic                                   | Baseline  | Good  | Better  | Best
---                                     | ---       | ---   | ---     | ---
***Chapter 3***                         |           |       |         |
Templates                               | x         |       |         |
Template Inheritance                    | x         |       |         |
Views                                   | x         |       |         |
Class-Based Views                       | x         |       |         |
URLs                                    | x         |       |         |
Routing                                 | x         |       |         |
***Chapter 4***                         |           |       |         |
Model Classes                           | x         |       |         |
Django Admin configuration              | x         |       |         |
Tests                                   |           | x     |         |
***Chapter 5***                         |           |       |         | 
Static Files                            | x         |       |         |
Queries                                 | x         |       |         |
***Chapter 6***                         |           |       |         |
Class-Based Forms                       | x         |       |         |
***Chapter 7***                         |           |       |         |
Authentication                          | x         |       |         |
Social auth integration                 |           | x     |         |
Postgres                                |           | x     |         |
***Chapter 8***                         |           |       |         |
Custom user models                      |           | x     |         |
Ad hoc forms                            |           | x     |         |
***Chapter 10***                        |           |       |         |
Bootstrap                               | x         |       |         |
***Chapter 11***                        |           |       |         |
Custom templates                        |           | x     |         |
Account management                      |           | x     |         |
***Chapter12***                         |           |       |         |
Email                                   |           | x     |         |
***Chapter 13***                        |           |       |         |
django_crispy_forms                     |           | x     |         |
***Chapter 14***                        |           |       |         | 
authorization                           |           | x     |         |
CBV mixins                              |           | x     |         |
***Chapter15***                         |           |       |         |
ManytoMany relationships                |           | x     |         |
***Chapter16***                         |           |       |         |
heroku deployment                       |           |       | x       |
vps deployment (nginx, gunicorn)        |           |       | x       |
Static assets with nginx and whitenoise |           | x     |         |
Securing with SSL                       | x         |       |         |
Custom middlewre                        |           |       | x       |
Task scheduling with cron               |           | x     | x       |
CI/CD with Github                       |           |       |         | x
***3rd Party***                         |           |       |         |
[Django admin](https://github.com/wsvincent/awesome-django#admin) | | | | x
[APIs](https://github.com/wsvincent/awesome-django#apis) | |  |         | x
[Async](https://github.com/wsvincent/awesome-django#async) |           |       |         | x
[ECommerce](https://github.com/wsvincent/awesome-django#ecommerce) |    |   |   | x
[Files and Images](https://github.com/wsvincent/awesome-django#filesimages) |    |   |   | x
[Model enhancements](https://github.com/wsvincent/awesome-django#models) |   |   |   | x
[Search](https://github.com/wsvincent/awesome-django#search) |   |   |   | x
[Tasks and Job Scheduling](https://github.com/wsvincent/awesome-django#task-queues) |   |   |   | x
[Users and SSO](https://github.com/wsvincent/awesome-django#users) |   |   |   | x
[Views](https://github.com/wsvincent/awesome-django#views) |   |   |   | x
