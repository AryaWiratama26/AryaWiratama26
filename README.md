```python
class Developer:
    def __init__(self):
        self.name = "Arya Wiratama"
        self.role = "Computer Lab Assistant"
        self.passion = ["programming", "problem_solving"]
        self.primary_languages = ["Python", "C++"]
        self.current_task = "helping students with technical tasks"
        
    def get_tech_stack(self):
        return {
            "languages": ["Python", "C++", "C#", "JavaScript", "C", "PHP"],
            "web": ["Node.js", "HTML5", "CSS3", "Bootstrap"],
            "database": ["MySQL", "MariaDB"],
            "tools": ["Linux", "Git", "Bash"],
        }
    
    def daily_routine(self):
        activities = [
            "solve_programming_problems()",
            "assist_students_with_code()", 
            "debug_technical_issues()",
            "learn_new_technologies()"
        ]
        return activities

me = Developer()
print(f"Welcome to {me.name}'s GitHub profile")
print(f"Role: {me.role}")
```

```python
# Skills progression
skills = {
    "python": {"level": 90, "years": 3},
    "cpp": {"level": 85, "years": 2},
    "javascript": {"level": 75, "years": 2},
    "mysql": {"level": 70, "years": 1}
}

def display_skills():
    for skill, data in skills.items():
        bar = "█" * (data["level"] // 10) + "░" * (10 - data["level"] // 10)
        print(f"{skill.upper():<12} {bar} {data['level']}%")

display_skills()
```

```python
# Current status
status = {
    "working_on": "student programming assistance",
    "learning": "machile learning",
    "goal": "ml eng"
}

def current_focus():
    return f"Currently {status['working_on']} while {status['learning']}"

print(current_focus())
```

## GitHub Statistics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=AryaWiratama26&show_icons=true&theme=dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AryaWiratama26&layout=compact&theme=dark&hide_border=true)

```python
# Contact information
contacts = {
    "linkedin": "https://www.linkedin.com/in/arya-wiratama-60a059345/",
    "instagram": "https://www.instagram.com/wirarya_",
    "github": "https://github.com/AryaWiratama26"
}

def connect_with_me():
    return contacts

```

```bash
# Let's collaborate
git clone https://github.com/AryaWiratama26/collaboration.git
cd collaboration
./lets_work_together.sh
```