---
permalink: /
title: "AI, language & human decisions."
classes: home-profile
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="research-intro" markdown="1">
<p class="research-eyebrow">RESEARCH / BUILD / TRANSLATE</p>

Hey there! I'm **James** (j1m) – a **PhD student** at The University of Queensland (UQ), where I explore **Natural Language Processing (NLP)**, **Machine Learning (ML)**, and **Information Systems**.

When I'm not diving into research or teaching, you’ll find me working on fun and impactful tech projects that bridge academic knowledge with real-world applications.

<div class="research-actions">
  <a class="research-button" href="{{ '/publications/' | relative_url }}">Explore my research <span aria-hidden="true">↗</span></a>
  <a class="research-text-link" href="{{ '/research-projects/' | relative_url }}">Current projects <span aria-hidden="true">→</span></a>
</div>
</div>

## Research in practice

AI-enabled translation for more accessible science and emergency communication.

{% include research-projects.html %}

## Latest publications

{% assign latest_publications = site.publications | sort: "date" | reverse %}
<div class="latest-publications">
{% for publication in latest_publications limit:2 %}
  <article>
    <p class="research-eyebrow">{{ publication.date | date: '%Y' }} / {% if publication.category == 'manuscripts' %}JOURNAL ARTICLE{% else %}CONFERENCE PAPER{% endif %}</p>
    <h3><a href="{{ publication.url | relative_url }}">{{ publication.title }}</a></h3>
    <p>{{ publication.venue }}</p>
  </article>
{% endfor %}
</div>

[View all publications and presentations →]({{ '/publications/' | relative_url }})

---

{% include awards.html %}

### 🔍 What I Do

- 📚 **PhD Researcher**: Exploring NLP & ML applications to improve how we process information. 🧠
- 🧑‍🏫 **Casual Academic at UQ**: Teaching students to apply machine learning in real-world scenarios.
- 💻 **Former Full Stack Developer at KPMG**: Developing data-driven, AI-powered solutions for clients.
- 🌏 **Location**: Brisbane, Australia

---


### 📊 GitHub Activity

[View my GitHub activity and contributions →](https://github.com/james-boyce)

---

### 💡 My Recent Talks & Research

- **Improving News Validation with NLP**  
  How can we move beyond lexical features to enhance the validation of online news?

- **Generative AI in Digital Nudging**  
  Exploring the capabilities of **GenAI** with digital nudging 🪙.

- **Iterative Topic Modeling**  
  A novel approach to improve unsupervised topic modeling with **seed word generation** 🔑.

---

### 🌟 Fun Stats

- 🔥 **GitHub Contributions**: 30+ this year 🎉
- 🧑‍💻 **Languages I Speak**: Python, JavaScript, SQL, a bit of R! 🐍
- 🎓 **Favorite Tool**: Jupyter Notebooks for rapid prototyping 💡
- 📅 **Current Focus**: Advancing NLP & ML methods for practical applications that help people.

---

Thanks for stopping by! Feel free to explore my projects, read my research papers, or just say hello 👋. I'm always open to collaboration and new ideas!

🚀 **Keep learning, keep coding!**
