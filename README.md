### Hi there 👋

Here are some ideas to get you started:

- 🔭 I’m currently a Front-End student 
- 🌱 I’m currently learning NodeJS
- 👯 I like HTML, CSS and JavaScript 
- 😄 Pronouns: Ela/Dela


<div align="center">
<a href="https://https://github.com/natttsilv">
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=natttsilv&show_icons=true&theme=dracula&include_all_commits
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=natttsilv&layout=compact&langs_count=7&theme=dra
</div>
<div style="display: inline_block"><br>
<img align="center" alt="Dev-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/ja
<img align="center" alt="Dev-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/ty
<img align="center" alt="Dev-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/reac
<img align="center" alt="Dev-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5
<img align="center" alt="Dev-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-o
</div>
##
<div>
<a href="https://www.youtube.com/channel/UC44Y7HUcjOu200dbBYjSjjQ" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?s
<a href="AQUI VAI O LINK DO INSTAGRAM" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&log
<a href = "mailto:devbatistacontato@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoCo
<a href="AQUI VAI O LINK DO LINKEDIM" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=
![Snake animation](https://github.com/DevBatista1/DevBatista1/blob/output/github-contribution-grid-snake.svg)
</div>

como personalizar o seu perfil no github Readme 2
Segundo código utilizado no vídeo, código da cobrinha:
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
github_user_name: DevBatista1
svg_out_path: dist/github-contribution-grid-snake.svg
- uses: crazy-max/ghaction-github-pages@v2.1.3
with:
target_branch: output
build_dir: dist
env:
GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
