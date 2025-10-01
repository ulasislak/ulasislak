<div align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<h1 align="center">Merhaba, ben [Adınız] 👋</h1>

<div align="center">
  <a href="https://github.com/ulasislak">
    <img src="https://github-readme-stats.vercel.app/api?username=ulasislak&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  </a>
  <a href="https://github.com/ulasislak">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ulasislak&layout=compact&langs_count=8&theme=dracula"/>
  </a>
</div>

<div align="center">
  <h3>⚡ Yeteneklerim ⚡</h3>
  <p>
    <a href="https://skillicons.dev">
      <img src="https://skillicons.dev/icons?i=js,html,css,react,nodejs,express,mongodb,mysql,git,github,vscode&perline=5" />
    </a>
  </p>
</div>

<div align="center">
  <h3>🔗 Sosyal Medya Hesaplarım 🔗</h3>
  <p>
    <a href="https://www.linkedin.com/in/kullanici-adiniz/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="https://twitter.com/kullanici-adiniz">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
    </a>
     <a href="mailto:email-adresiniz">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
  </p>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ulasislak&theme=dracula&hide_border=true" />
</div>

<style>
  /* Genel Stiller */
  div {
    margin-bottom: 20px;
  }
  h1, h3 {
    color: #58a6ff; /* Mavi renk */
  }
  img {
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
  }
  img:hover {
    transform: scale(1.05);
  }
</style>

<script>
  // JavaScript ile dinamik bir şeyler ekleyebilirsiniz.
  // Örneğin, bir "typing" efekti.
  const nameElement = document.querySelector('h1');
  const nameText = nameElement.innerText;
  nameElement.innerText = '';

  let i = 0;
  function typeWriter() {
    if (i < nameText.length) {
      nameElement.innerHTML += nameText.charAt(i);
      i++;
      setTimeout(typeWriter, 150);
    }
  }
  typeWriter();
</script>
