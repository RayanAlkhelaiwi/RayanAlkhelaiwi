## Hey there! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="24">

<!-- Zero width character is used to put extra blank lines before and after code -->

<h3>
    
```python

from __future__ import annotations
import json, dataclasses as dc

@dc.dataclass
class Skills:
    languages  : tuple[str, ...] = ('Ruby', 'Python', 'JavaScript')
    frameworks : tuple[str, ...] = ('Rails', 'Flask', 'React')
    databases  : tuple[str, ...] = ('MySQL', 'PostgreSQL', 'Redis')
    deployment : tuple[str, ...] = ('Docker', 'Sidekiq', 'RabbitMQ')

    def jsonify(self) -> str:
        return json.dumps(dc.asdict(self), indent=4)

skills = Skills()
print(skills.jsonify())
​
```
</h3>

<div>
    <div>
        <a href="https://rayan.dev" target="_blank">
            <img src="https://img.shields.io/badge/rayan.dev-portfolio?style=flat-square&color=00A3B8&logoColor=white&logo=ghost"/>
        </a>
        <a href="https://twitter.com/RayanAlkhelaiwi" target="_blank">
            <img src="https://img.shields.io/badge/RayanAlkhelaiwi-twitter?style=flat-square&color=1DA1F2&logoColor=white&logo=twitter"/>
        </a>
        <a href="https://linkedin.com/in/RayanAlkhelaiwi" target="_blank">
            <img src="https://img.shields.io/badge/RayanAlkhelaiwi-linkedin?style=flat-square&color=0077B5&logoColor=white&logo=linkedin"/>
        </a>
        <a href="mailto:rayan@hey.com" target="_blank">
            <img src="https://img.shields.io/badge/rayan-hey?style=flat-square&color=400B9B&logoColor=white&logo=hey"/>
        </a>
        <a href="https://dev.to/rayan" target="_blank">
            <img src="https://img.shields.io/badge/rayan-devto?style=flat-square&color=1F1F1F&logoColor=white&logo=dev.to"/>
        </a>
    </div>
    <div align="right">
        <a href="https://dev.to/rayan" target="_blank">
            <img src="./assets/hacktoberfest2019.png" height="80"/>
        </a>
    </div>
</div>

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
