```python
class Berserkware:
  def __init__(self):
    self.name = 'Caleb'
    self.favouriteMusic = 'Green Day'
    self.favouriteFood = 'Apples'
    
  @property
  def skills(self):
    return [
      'Python',
      'Django',
    ]
    
  @property
  def hobbies(self):
    return [
      'Coding',
      'Drawing',
      'Reading',
      'Biking',
    ]
    
  @property
  def currentProjects(self):
    return {
      'Computense': 'A geekforgeeks clone made with Django',
      '[NAME REDACTED]': 'A Python web library like Django but without the junk you don't need',
    }
    
  @property
  def TODO(self):
    return [
      'Learn JavaScript',
      'Learn C and C++',
      'Learn Java',
      'Learn HTML/CSS',
      'Learn Docker, Kubernetes and NGINX',
      'Do some Machine Learning',
    ]
    
  @property
  def ContactMe(self):
    return {
      'Email': 'berserkware@gmail.com',
      'Discord': 'King0fLegends#8916',
    }
```
