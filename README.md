- ## Olá, me chamo Diogo Leonardo 
- 👀 Busco conhecimento na área da programação 
- 🌱 Estou aprendendo sobre Desenvolvimento Web (Front-End) 
- 💞️ Estou buscando novos projetos!
- 📫 Como me encontrar, diogoleo57@gmail.com

<div align="center">
  <a href="https://github.com/DiogoLeonardoo">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=DiogoLeonardoo&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DiogoLeonardoo&layout=compact&langs_count=7&theme=dark"/>
</div>
  
  ![Snake animation](https://github.com/DiogoLeonardoo/DiogoLeonardoo/blob/output/github-contribution-grid-snake.svg)
  
  name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<!---
DiogoLeonardoo/DiogoLeonardoo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
