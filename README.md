
## :sparkles: Hi there, I am here:   

<div dir="ltr">

```python
from abc import ABC, abstractmethod
from dataclasses import dataclass


class Human(ABC):
    @abstractmethod
    def say_hello(self):
        pass


@dataclass
class InformationMixin:
    full_name: str
    location: str
    language: str


@dataclass
class Developer(Human, InformationMixin):

    def say_hello(self):
        print('Glad to have you here. I hope you will be interested in my projects')      
        

jeff = Developer('Seyed-Jafar-Yaghoubi', 'Iran', 'Persian')   
jeff.say_hello()

```
<!--
</div>
<div align="left">
    <picture align="right">
        <img align="right" width="140em" height="140em" src="https://github.com/J-Yaghoubi/J-Yaghoubi/blob/main/programming.gif">
    </picture>
<br>
</div>
-->

 <br>

 ## 🛠 &nbsp;Tech Stack

![Python](https://img.shields.io/badge/Python-FFD43B?style=flat&logo=python&logoColor=blue)&nbsp;
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=green)&nbsp;
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)&nbsp;
![Mongo DB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)&nbsp;
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?&style=flat&logo=redis&logoColor=white)&nbsp;
![ELASTICSEARCH](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)&nbsp;
![CELERY](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)&nbsp;
![RABBITMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)&nbsp;
![LINUX](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)&nbsp;
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=flat&logo=docker&logoColor=white)&nbsp;
![GRAFANA](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)&nbsp;
![PROMETHEUS](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)&nbsp;
![JENKINS](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)&nbsp;
![Git](https://img.shields.io/badge/GIT-E44C30?style=flat&logo=git&logoColor=white)&nbsp;
![NGINX](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)&nbsp;
![C-Sharp](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)&nbsp;
![LUA](https://img.shields.io/badge/Lua-2C2D72?style=flat&logo=lua&logoColor=white)&nbsp;
