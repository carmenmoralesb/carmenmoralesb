<h2> Hi, I'm Carmen! <img src="https://64.media.tumblr.com/3a73e5262fd831183eed007eeade43fc/68cc2ff2cf54d73a-cd/s1280x1920/ce4d6a9c87202765f9bcf39d19b7d35e9cfdc62b.png" width="50"></h2>
<img align='right' src="https://64.media.tumblr.com/41be79180679dc28a4d0459deb9de4ea/254f5dee0c222861-e3/s1280x1920/9ecf7066ea260ff8c9ae4bea14d173e1d536fe9a.gifv" width="230">
</br><em>Android Developer at <a href="https://www.sdos.es/home">SDOS :heart:
</em></p>

[![Linkedin: carmenmorales](https://img.shields.io/badge/-linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/carmenmoralesbonet/)](https://www.linkedin.com/in/carmenmoralesbonet/)
[![GitHub Carmen](https://img.shields.io/github/followers/carmenmoralesb?label=follow&style=social)](https://github.com/carmenmoralesb)


### :sparkles: Know me!!

```python

import datetime # we will use this for date objects

class Person:

    def __init__(self, name, surname, birthdate, address, telephone, email):
        self.name = name
        self.surname = surname
        self.birthdate = birthdate

        self.address = address
        self.telephone = telephone
        self.email = email

    def age(self):
        today = datetime.date.today()
        age = today.year - self.birthdate.year

        if today < datetime.date(today.year, self.birthdate.month, self.birthdate.day):
            age -= 1

        return age
person = Person(
    "Carmen",
    "Morales Bonet",
    datetime.date(1995, 4, 26), # year, month, day
    "San Fernando,Cadiz",
    "Web/Mobile Developer",
    "carmen.morales.bonet@gmail.com"
)
```

✨ <em> You can contact me if you want! :)</em>

---
