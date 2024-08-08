```python
class Scientist:
  def __init__(self, age: int, university: str, research: List[str]) -> None:
      self.age: int = age
      self.university: str = university
      self.research: List[str] = research

Will = Scientist(
  age = 21,
  university = 'Rutgers University',
  research = ['Computational biology', 'Gene regulation', 'Deep Learning'],
)
```
