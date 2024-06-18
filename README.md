```python
class JuaniVillanueva:
    def __init__(self):
        self.name = "Juani Villanueva"
        self.location = "Argentina"
        self.pursuit = "Computer Science degree"
        self.languages = ["English", "Spanish"]
        self.technologies = ["Flutter", "Moodle", "MySQL/Postgre", "Firebase", "Docker", "Git/GitHub", "Xcode/Android Studio"]
        self.programming_languages = ["Dart", "Python", "Java", "Ruby", "C"]

    def __str__(self):
        return (
            f"Hey there! I'm {self.name} from {self.location}, pursuing a {self.pursuit}.\n"
            f"Languages: {', '.join(self.languages)}\n"
            f"Technologies: {', '.join(self.technologies)}\n"
            f"Programming Languages: {', '.join(self.skills)}\n"
            "Feel free to explore my repositories and connect with me!"
        )
        
# Usage
profile = JuaniVillanueva()
print(profile)
```
