<h1 align="center">Hi 👋, I'm Mikhail</h1>
<h1 align="center">Now work💼 at LWO 
  <a href="https://lwo.by" target="_blank"> <img src="https://firebasestorage.googleapis.com/v0/b/project-486c6.firebasestorage.app/o/lwo-logo.png?alt=media&token=89d6c1b2-0c82-4ada-8f4e-033e99ac1947" alt="LWO" width="40" height="40"/> </a> 
  <br>Since 21.10.2024 | Working for <span id="work-duration">0 days</span>
</h1>
<h3 align="center">Languages and Tools:</h3>
<p align="center"> 
  <a href="https://www.java.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> 
  <a href="https://www.spring.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" alt="spring" width="40" height="40"/> </a> 
  <a href="https://flutter.dev" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="flutter" width="40" height="40"/> </a> 
  <a href="https://nodejs.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="nodejs" width="40" height="40"/> </a> 
  <a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="html5" width="40" height="40"/> </a> 
  <a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="css3" width="40" height="40"/> </a> 
  <a href="https://www.oracle.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> 
  <a href="https://www.postgresql.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> 
  <a href="https://firebase.google.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/firebase/firebase-original.svg" alt="firebase" width="40" height="40"/> </a> 
  <a href="https://www.mongodb.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="html5" width="40" height="40"/> </a> 
</p>

<p align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bibimotik&layout=donut&theme=radical" alt="Bibimotik" />
</p>
<div align="center" id="badges">
  <a align="center" href="https://www.instagram.com/bibim0tik/">
    <img src="https://img.shields.io/badge/Instagram-orange?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  <a align="center" href="https://t.me/bibimotik">
    <img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
</div>

<script>
  function updateWorkDuration() {
    const startDate = new Date('2024-10-21');
    const currentDate = new Date();
    
    const diffTime = currentDate - startDate;
    const diffDays = Math.floor(diffTime / (1000 * 60 * 60 * 24));
    
    const months = Math.floor(diffDays / 30.44);
    const days = Math.floor(diffDays % 30.44);
    
    document.getElementById('work-duration').textContent = 
      `${months} months ${days} days`;
  }
  
  updateWorkDuration();
  // Обновляем каждые 24 часа
  setInterval(updateWorkDuration, 86400000);
</script>
