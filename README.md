<h2> Hi, I'm Carmen! 
    ![Kotlin](https://img.shields.io/badge/kotlin-%230095D5.svg?style=for-the-badge&logo=kotlin&logoColor=white) 
</h2>
</br><em>Developer at <a href="https://www.sdos.es/home">SDOS :heart:
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
