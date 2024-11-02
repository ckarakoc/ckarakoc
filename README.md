<style>
  .header {
    display: flex;
    margin-top: 10px;
    padding: 0;
    align-items: center; 
    /*justify-content: center;*/
    justify-content: space-between;
  }

  .header h1 {
    margin: 0;
    padding: 0;
  }
  
  .header .wave {
    width: 30px;
    height: 30px;
  }
  
  .header .mode {
    width: 50px;
    height: 50px;
    margin-left: 10px; /* Adds spacing between text and image */
  }

  .gh-stats-1 { grid-area: top; }
  .gh-stats-2 { 
    display: flex;
    grid-area: bot; 
    align-items: baseline;
    justify-content: space-evenly;
  }
  .gh-stats {
    display: grid;
    grid-template-areas: 
      'top top top'
      '. bot .';
    text-align: center;
  }

  .social-links {
    display: flex;
    gap: 3px;
    flex-wrap: wrap;
  }

  .outer-tag {
    display: flex;
    align-items: center;
    /*justify-content: center;*/
    margin: 2px;
  }

  .outer-tag img {
    margin:0;
    padding: 0;
    height: 30px;
    width: auto;
  }

  .outer-tag img:nth-child(2) {
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
  }

  .outer-tag .earth {
    background-color: darkblue;
    border-top-left-radius: 150px;
    border-bottom-left-radius: 150px;
    padding: 0;
    margin: 0;
  }

 .outer-tag .linkedin {
    background-color: #0274B3;
    border-top-left-radius: 15px;
    border-bottom-left-radius: 15px;
    padding: 0;
    margin: 0;
  }

 .outer-tag .resume {
    background-color: #0274B3;
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
    padding: 0;
    margin: 0;
  }

  .outer-tag .ghpages {
    background-color: #0274B3;
    border-top-left-radius: 15px;
    border-bottom-left-radius: 15px;
    padding: 0;
    margin: 0;
  }

  .outer-tag .codewars {
    animation: pulse 1s infinite;
    /*background-color: darkred;*/
    border-top-left-radius: 15px;
    border-bottom-left-radius: 15px;
    padding: 0;
    margin: 0;
  }

  .outer-tag .codewars-wrapper {
    background-color: darkred;
    border-top-left-radius: 15px;
    border-bottom-left-radius: 15px;
    padding: 0;
    margin: 0;
    height: 30px;
    width: auto;
  }

  @keyframes pulse {
    0% {
      opacity: 0;
    }
    50% {
      transform: scale(1.4);
      opacity: 0.4;
    }
  }
</style>

<br/>

<div class="header">
    <h1>Hi there<img src="wave.gif" class="wave" alt="wave"> I am <br/> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&lines=Celal+Karako%C3%A7;Software+Engineer" alt="Typing SVG" /> </h1>
    <picture class="mode">
      <source media="(prefers-color-scheme: dark)" srcset="moon.png">
      <source media="(prefers-color-scheme: light)" srcset="sun.png">
      <img alt="Sun" src="sun.png">
    </picture>
</div>

<div class="gh-stats">
<div class="gh-stats-1">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=ckarakoc&theme=vue-dark&show_icons=true&hide_border=false&count_private=true&rank_icon=github">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=ckarakoc&theme=vue&show_icons=true&hide_border=false&count_private=true&rank_icon=github">
  <img alt="Fallback" src="https://github-readme-stats.vercel.app/api?username=ckarakoc&theme=vue-dark&show_icons=true&hide_border=true&count_private=true&rank_icon=github">
</picture>
</div>
<div class="gh-stats-2">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=ckarakoc&theme=vue-dark&hide_border=true">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=ckarakoc&theme=vue&hide_border=true">
  <img alt="Fallback" src="https://github-readme-streak-stats.herokuapp.com/?user=ckarakoc&theme=vue-dark&hide_border=true">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=ckarakoc&theme=vue-dark&show_icons=true&hide_border=true&layout=compact">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=ckarakoc&theme=vue&show_icons=true&hide_border=true&layout=compact">
  <img alt="Fallback" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ckarakoc&theme=vue-dark&show_icons=true&hide_border=true&layout=compact">
</picture>
</div>
</div>


<div class="social-links">
<a class="outer-tag" href="https://www.linkedin.com/in/celal-karakoç/">
  <img alt="linkedin" class="linkedin" src="linkedin.gif">
  <img alt="linkedin2" title="linkedin2" class="linkedin2" src="https://img.shields.io/badge/-linkedin-0274B3?style=for-the-badge"/>
</a>

<a class="outer-tag" href="https://www.ckarakoc.nl/">
  <img alt="earth" class="earth" src="earth.gif">
  <img alt="earth2" title="earth2" class="earth2" src="https://img.shields.io/badge/-website-darkblue?style=for-the-badge"/>
</a>

<a class="outer-tag" href="https://www.ckarakoc.nl/CV.pdf">
  <img alt="resume" class="resume" src="document.gif">
  <img alt="resume2" title="resume2" class="resume2" src="https://img.shields.io/badge/-resume-000000?style=for-the-badge"/>
</a>

<a class="outer-tag" href="https://ckarakoc.github.io/">
  <img alt="ghpages" class="ghpages" src="github.gif">
  <img alt="ghpages2" title="ghpages2" class="ghpages2" src="https://img.shields.io/badge/-portfolio-fff?style=for-the-badge"/>
</a>

<a class="outer-tag" href="https://www.codewars.com/users/ckarakoc">
  <div class="codewars-wrapper">
  <img alt="codewars" class="codewars" src="codewars.png">
  </div>
  <img alt="codewars2" title="codewars2" class="codewars2" src="https://img.shields.io/badge/-codewars-darkred?style=for-the-badge"/>
</a>
</div>
