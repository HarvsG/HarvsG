### Welcome to me.py
[![An image of @harvsg's Holopin badges, which is a link to view their full Holopin profile](https://holopin.me/harvsg)](https://holopin.io/@harvsg)
<!--
**HarvsG/HarvsG** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


```python
class Me(Doctor, Developer):
    username: str = "HarvsG"
    website: str = "www.codingdoctor.co.uk"
    contact: str = "doctor@codingdoctor.co.uk"

    can_code: List[str] = [
        "Python",
        "R",
        "Dart",
        "Flutter",
        "JavaScript",
    ]

    medical: Dict[str, List[str]] = {
        "currentRoles": [
            "Anaesthetics Higher Specialist Training",
            "Intensive Care Medicine Higher Specialist Training",
        ],
        "completedRoles": [
            "Medical School",
            "FY1",
            "FY2",
            "Medical Education FY3",
            "Primary FRCA",
            "ACCS Anaesthetics",
            "Final FRCA",
        ],
        "toGo": ["FCICM", "CCT"],
        "nerdyInterests": [
            "Physiology",
            "Home Automation",
            "Pre-hospital Medicine",
            "Evidence Based Medicine",
            "Machine Learning",
            "Personal Finance",
        ],
    }

    ongoing_projects: List[str] = [
        "Cohort study into ECG criteria for LVH",
        "Tinkering with raspberry pi cluster",
        "Home automation using and contributing to HomeAssistant",
    ]


me: Me = Me()
```
