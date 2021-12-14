## Oie eu sou a Jaina Barcelos ♡
 
- 🌱  Atualmente  estou na faculd de Ciência da Computação;
- 📫 jainabarcelos12@gmail.com
- 😀 Pronouns: ela/dela

<div align="center">
  <a href="https://github.com/jay-barcelos">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=jay-barcelos&show_icons=true&theme=aura&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jay-barcelos&layout=compact&langs_count=7&theme=aura"/>
</div>
  
##
  
  <div>
      <img align="right" alt="Jay" src="file:///home/usuario/Downloads/Jay-gif%20(1).mp4">
  </div>
  
  ![Snake animation](https://github.com/jay-barcelos/jay-barcelos/blob/output/github-contribution-grid-snake.svg)

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
          github_user_name:  jay-barcelos
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  




 
    
    
    
  
    
   
                                       
                                       
                                       
    
    










