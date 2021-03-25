# :computer: Welcome to my page!
![visitors](https://visitor-badge.laobi.icu/badge?page_id=noelledons.visitor-badge)
<br>

```python
# python

class SoftwareDeveloper:
    def __init__(self):
        self.name = "Noelle Donkor"
        self.role = "Software Developer"
        self.location = "London"
        self.portfolio = "https://noelledonkor.com/"
        self.knowledge_base = [
            "Web Development",
            "Data Science",
            "Volunteering and",
            "Food",
        ]
        self.knowledge_base.insert(0, "Frontend and Backend Technologies")

    def say_hi(self):
        print(
            """Hello there, thanks for stopping by!
            
            My name is {name}, an aspiring {role} based in London, UK.
            
            Recently, I have been focusing on understanding {focus} for my personal development.
            
            I have a wide range of interests, but most of them are {knowledge_base}.
            
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


## 📫 **How to reach me**
- LinkedIn: [Noelle Donkor](https://www.linkedin.com/in/noelle-donkor/)
- Website: [noelledonkor.com](https://noelledonkor.com/)
- Medium: [https://noelledons.medium.com/](https://noelledons.medium.com/)

