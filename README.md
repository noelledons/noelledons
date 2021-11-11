# :computer: Welcome to my page!
![visitors](https://visitor-badge.laobi.icu/badge?page_id=noelledons.visitor-badge)
<br>

```python
# python

class SoftwareDeveloper:
    def __init__(self):
        self.name = "Noelle"
        self.role = "Software Developer"
        self.location = "London"
        self.portfolio = "https://noelledonkor.com/"
        self.knowledge_base = [
            "Food",
            "Skincare and",
            "Haircare!",
        ]
        self.knowledge_base.insert(0, "Frontend and Backend Technologies")

    def say_hi(self):
        print(
            """Hello there, thanks for stopping by!
            
            My name is {name}, a {role} based in {location}.
            
            During the day, I spend my spare time learning about {focus}, and at Night, I love all things {knowledge_base}
            
            Do you want to know more about me? View my personal portfolio here: {portfolio}""".format(
            
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
                portfolio=self.portfolio,
            )
        )

me = SoftwareDeveloper()
me.say_hi()
```

## :atom: **Project Directory**
- My Projects: [Project Directory](https://github.com/noelledons/project-directory)

## 📫 **How to reach me**
- LinkedIn: [Noelle Donkor](https://www.linkedin.com/in/noelle-donkor/)
- Website: [noelledonkor.com](https://noelledonkor.com/)
- Medium: [https://noelledons.medium.com/](https://noelledons.medium.com/)

