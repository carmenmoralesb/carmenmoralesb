<h2> Hi, I'm Carmen! <img src="https://como-funciona.com/wp-content/uploads/2019/08/python.png" width="50"> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbYXuyL7OASrkmLkYDqKN4FQMC1CBZv0tIaw&usqp=CAU" height="50" width="50"></h2>
<img align='right' src="https://i.pinimg.com/originals/20/61/91/20619103a1d2790a691475c613fa8031.jpg" height="50" width="50">
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
