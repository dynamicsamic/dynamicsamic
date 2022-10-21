```python
from dataclasses import dataclass


@dataclass
class Pythonista:
    name: str
    position: str
    attitude: str
    status: str

    def greet(self):
        print(
            f"Hi! My name is {self.name}, I'm a {self.position}. "
            f"I'm {self.attitude} to learn something new in "
            f"the world of Python. My current status: {self.status}."
        )


dynamicsamic = Pythonista(
    "Sam", "Hobby developer", "eager", "switching career to tech"
)
dynamicsamic.greet()
```
