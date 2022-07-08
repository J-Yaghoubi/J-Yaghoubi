## Hi there 👋

<div dir="ltr">

```python
from abc import ABC

class Creature(ABC):
    pass

class PersonalFeaturesMixin:
    def add_abilities(self) -> None:
        self.job_skills = ['Coding', 'Financial Markets Analyzing', 'Business']
        self.sport = ['Horseback Riding', 'Camping', 'Bodybuilding']
        self.favorites = ['Coffee', 'Games']
        
class Human(Creature, PersonalFeaturesMixin):
    def __init__(self, full_name: str, location: str, language: str) -> None:       
        self.full_name = full_name
        self.location = location
        self.language = language

    def say_hello(self):
        print('Glad to have you here. I hope you will be interested in my projects')        
        
jeff = Human('Seyed-Jafar-Yaghoubi', 'Iran', 'Persian')   
jeff.add_abilities() 
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

![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python)&nbsp;
![Django](https://img.shields.io/badge/-Django-05122A?style=flat&logo=django)&nbsp;
![Flask](https://img.shields.io/badge/-Flask-05122A?style=flat&logo=flask)&nbsp;
![Mongo DB](https://img.shields.io/badge/-MongoDB-05122A?style=flat&logo=mongodb)&nbsp;
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql)&nbsp;
![Redis](https://img.shields.io/badge/-Redis-05122A?style=flat&logo=redis)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![Docker](https://img.shields.io/badge/-Docker-05122A?style=flat&logo=docker)&nbsp;
