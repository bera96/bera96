# Hello there 👋

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareDeveloper:

    def __init__(self):
        self.name = "Bera Yılmazyurt"
        self.country = "Turkey"
        self.city = "Istanbul"
        self.role = "Software Developer"
        self.language_spoken = ["tr_TR", "en_US"]
        self.technologies = {
        "frontend": {
            "js": ["React", "Next.js"],
            "css": ["Sass", "Tailwind", "Bootstrap"],
            "uiLibraries": ["Material UI", "Ant Design", "Chakra UI"],
            "microFrontend": {
                "architectures": ["Module Federation", "Single-SPA"],
                "integrations": ["Webpack", "Vite"],
            },
        },
        "backend": {
            "js": ["Node", "Express", "NestJS"],
            "python": ["Django", "Odoo", "Flask"],
        },
        "mobile": {
            crossPlatform: ["React Native"],
        },
        "devops": ["Docker🐳", "CI/CD", "Nginx", "GitHub Actions"],
        "databases": ["PostgreSQL", "MongoDB", "MySQL", "SQLite", "Firebase Realtime DB", "redis"],
        "misc": ["Socket.IO", "REST APIs", "WebSockets"]
    },

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = SoftwareDeveloper()
me.say_hi()
```
