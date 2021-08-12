### Hey there! 👋

<!-- Zero width character is used to put extra blank lines before and after code -->

<h4>
    
```python

from __future__ import annotations
import json, dataclasses as dc

@dc.dataclass
class Skills:
    languages  : tuple[str, ...] = ('Python', 'Ruby', 'JavaScript')
    frameworks : tuple[str, ...] = ('Flask', 'Rails', 'React')
    databases  : tuple[str, ...] = ('PostgreSQL', 'MySQL', 'Redis')
    deployment : tuple[str, ...] = ('Celery', 'Kubernetes', 'RabbitMQ')

    def jsonify(self) -> str:
        return json.dumps(dc.asdict(self), indent=4)

skills = Skills()
print(skills.jsonify())
​
```
</h4>

<!--
**RayanAlkhelaiwi/RayanAlkhelaiwi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
