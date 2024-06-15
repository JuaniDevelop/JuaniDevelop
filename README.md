```python
class JuaniVillanueva:
    def __init__(self):
        self.name = "Juani Villanueva"
        self.location = "Argentina"
        self.pursuit = "Computer Science Degree"
        self.languages = ["English", "Spanish"]
        self.technologies = ["Flutter", "Moodle"]
        self.skills = ["Git", "GitHub", "Docker", "Firebase", "C", "Java", "Python", "Ruby"]

    def __str__(self):
        return (
            f"Hey there! I'm {self.name} from {self.location}, pursuing a {self.pursuit}.\n"
            f"Languages: {', '.join(self.languages)}\n"
            f"Technologies: {', '.join(self.technologies)}\n"
            f"Skills: {', '.join(self.skills)}\n"
            "Feel free to explore my repositories and connect with me!"
        )
        
# Usage
profile = JuaniVillanueva()
print(profile)
```
