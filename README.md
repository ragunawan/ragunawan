```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class human:

    def __init__(self):
        self.name = "Ryan Gunawan"
        self.role = "Computer Engineer"

    def works_on(self):
        self.code = ['python', 'javascript', 'java', 'c', 'c++', 'bash', 'perl']
        self.tools = ['vscode', 'docker', 'vim > emacs']
        self.db = ['oracle', 'postgresql', 'mysql', 'sqlite']
        self.infra = ['gitlab', 'azure']

    def say_hi(self):
        print("hello world 👋.")


me = human()
me.say_hi()
```

![visitors](https://visitor-badge.laobi.icu/badge?page_id=ragunawan)
