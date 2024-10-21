# Hello there 👋

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareDeveloper:

    def __init__(self):
        self.name = "Bera Yılmazyurt" 
        self.role = "Software Developer"
        self.language_spoken = ["tr_TR", "en_US"]
        self.technologies = {
        "frontEnd": {
            "js": ["React", "Next.js"],
            "css": ["Sass", "Tailwind", "Bootstrap"],
            "uiLibraries": ["Material UI", "Ant Design", "Chakra UI"],
        },
        "backEnd": {
            "js": ["Node", "Express", "NestJS"],
            "python": ["Django", "Odoo", Flask"],
        },
        "mobileApp": {
            crossPlatform: ["React Native"],
        },
        "devOps": ["Docker🐳", "CI/CD", "Nginx", "GitHub Actions"],
        "databases": ["PostgreSQL", "MongoDB", "MySQL", "SQLite", "Firebase Realtime DB", "redis"],
        "misc": ["Socket.IO", "REST APIs", "WebSockets"]
    },

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = SoftwareDeveloper()
me.say_hi()
```
