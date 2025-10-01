<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
  
  <h1 align="center">Selam, ben Ulaş! 👋</h1>
  
  <h3 align="center">
    <div id="subtext"></div>
  </h3>
  
  <div align="center">
    <a href="https://www.linkedin.com/in/ulasislak/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>    
    <a href="mailto:ulasislak06@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
    </a>
  </div>
</div>

<table align="center" style="width:100%; border:none;">
  <tr>
    <td width="50%" valign="top">
      <div align="center">
        <h3>📊 GitHub İstatistiklerim</h3>
        <img src="https://github-readme-stats.vercel.app/api?username=ulasislak&show_icons=true&theme=gruvbox&include_all_commits=true&count_private=true" alt="GitHub Stats"/>
        <br/>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ulasislak&layout=compact&langs_count=8&theme=gruvbox" alt="Top Languages"/>
      </div>
    </td>
    <td width="50%" valign="top">
      <div align="center">
        <h3>🏆 GitHub Başarımlarım</h3>
        <img src="https://github-profile-trophy.vercel.app/?username=ulasislak&theme=gruvbox&column=3&row=2&margin-w=15&margin-h=15" alt="GitHub Trophies"/>
      </div>
    </td>
  </tr>
</table>

<div align="center">
  <h3>🔥 Katkı Grafiğim</h3>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ulasislak&theme=gruvbox&hide_border=true" alt="GitHub Streak"/>
</div>

<div align="center">
  <h2>🛠️ Kullandığım Teknolojiler</h2>
  
  <h4>Frontend</h4>
  <p>
    <a href="https://skillicons.dev">
      <img src="https://skillicons.dev/icons?i=html,css,js,typescript,react,redux,tailwind,vite" />
    </a>
  </p>
  
  <h4>Backend</h4>
  <p>
    <a href="https://skillicons.dev">
      <img src="https://skillicons.dev/icons?i=nodejs,express,python,django,go" />
    </a>
  </p>
  
  <h4>Veritabanı & Diğerleri</h4>
  <p>
    <a href="https://skillicons.dev">
      <img src="https://skillicons.dev/icons?i=mongodb,mysql,postgresql,docker,git,postman,vscode" />
    </a>
  </p>
</div>

<style>
  #subtext {
    font-weight: 300;
    color: #c5c5c5;
  }
</style>

<script>
  const subtext = document.getElementById('subtext');
  const phrases = [
    'Ben bir Full-Stack Geliştiriciyim.',
    'Harika web uygulamaları oluşturuyorum.',
    'Teknoloji ve inovasyon tutkunuyum.',
    'Yeni şeyler öğrenmeyi seviyorum.'
  ];
  let i = 0;
  let j = 0;
  let currentPhrase = [];
  let isDeleting = false;

  function loop() {
    subtext.innerHTML = currentPhrase.join('');

    if (i < phrases.length) {
      if (!isDeleting && j <= phrases[i].length) {
        currentPhrase.push(phrases[i][j]);
        j++;
      }

      if (isDeleting && j <= phrases[i].length) {
        currentPhrase.pop(phrases[i][j]);
        j--;
      }

      if (j == phrases[i].length + 1) {
        isDeleting = true;
      }

      if (isDeleting && j === 0) {
        currentPhrase = [];
        isDeleting = false;
        i++;
        if (i == phrases.length) {
          i = 0;
        }
      }
    }
    const speed = isDeleting ? 50 : 120;
    setTimeout(loop, speed);
  }
  loop();
</script>
