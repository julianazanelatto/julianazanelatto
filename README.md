### Hi there 👋

I'm Juliana Mascarenhas, and I've been working in the IT field since 2010. Today I'm Data Scientis with a focus on Network Data Science, and I work as a Tech Education Specialist at DIO. I'm also a content creator on Youtube channels SR and SP. So... you can see now that I love contributing to the community by creating articles, videos and sharing valuable information about IT careers.




- 🔭 I’m currently working on DIO
- 📢 Youtube Channel SR: <a href="https://www.youtube.com/c/SimplificandoRedes" target="">Simplificando Redes</a>
- 📢 Youtube Channel SP: <a href="https://www.youtube.com/c/SimplificandoProgramacao" target="">Simplificando Programação</a>


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=julianazanelatto&show_icons=true&layout=compact&theme=dark)](https://github.com/anuraghazra/github-readme-stats)


# Blog posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

name: Latest blog post SR
on:
  schedule: # Run workflow automatically
    - cron: '0 * * * *' # Runs every hour, on the hour
  workflow_dispatch: # Run workflow manually (without waiting for the cron to be called), through the GitHub Actions Workflow page directly

jobs:
  update-readme-with-blog:
    name: Update this repo's README with latest blog posts
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v2
      - name: Pull in dev.to posts
        uses: gautamkrishnar/blog-post-workflow@v1
        with:
          feed_list: "https://simplificandoredes.com/en/where-to-start-in-the-data-science-career/"


<!--

![](https://komarev.com/ghpvc/?username=julianazanelatto)


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=julianazanelatto&show_icons=true&theme=dark)

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a> 
-->
 
 
<!--
**julianazanelatto/julianazanelatto** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
