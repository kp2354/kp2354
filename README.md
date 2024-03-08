### Hi there 👋

<!--
**kp2354/kp2354** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

## ✉️ Find me on:


<p align="center">
 <a href="https://charalambosioannou.github.io/" target="_blank" rel="noopener noreferrer"> <img src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" alt="Python" height="40" style="vertical-align:top; margin:4px"> </a>
 <a href="https://linkedin.com/in/charalambosioannou" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" alt="Python" height="40" style="vertical-align:top; margin:4px"></a>
 <a href="mailto:cioannou1997@gmail.com"> <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" alt="Python" height="40" style="vertical-align:top; margin:4px"></a>
</p>

![](https://visitor-badge.laobi.icu/badge?page_id=kp2354.kp2354)
[![Github](https://img.shields.io/github/followers/kp2354?label=Follow&style=social)](https://github.com/kp2354)
<br />
# Blog posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

name: Latest blog post workflow
on:
  schedule:
    # Runs every hour
    - cron: '0 * * * *'
  workflow_dispatch:

jobs:
  update-readme-with-blog:
    name: Update this repo's README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: gautamkrishnar/blog-post-workflow@master
        with:
          feed_list: "https://dev.to/feed/kp2354"
## 🧰 Languages and Tools:
<p align="center">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" alt="Python" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" alt="Javascript" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" alt="VS Code" height="40" style="vertical-align:top; margin:4px">
</p>
