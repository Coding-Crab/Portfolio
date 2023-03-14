<script setup>

</script>

<template>

<div className="d-flex">

    <header>
      <img className="profile-banner" src="./assets/banner.png">
      <img className="profile-image" src="./assets/Profile.JPG">
      <div className="profile-detail">
        <h1>Aziz Saidi</h1>
        <span>Junior Developer</span>
      </div>
    </header>
  
    <article>
      <h1>About me</h1>
      <p>I'm a Creative Director and Designer from Tunis, Tunisia. I specialize in web development and print media. I enjoy turning complex problems into simple, beautiful, and intuitive designs.</p>
      <p>My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way. I've created web designs for many famous brand companies that you can refer to in my portfolio.</p>
      <div className="articleFooter">
        <p><a href="https://crocode-portfolio.surge.sh/">@Crocode</a></p>
        <div className="articleFooterImg">
          <ul>
            <li><a href="https://github.com/CrocodileCode">
            <img src="./assets/github.png" alt="github">
          </a> </li>
          <li><a href="https://www.instagram.com/aziz__saidi_">
            <img src="./assets/instagram.png" alt="instagram">
          </a> </li>
          </ul>
        </div>
      </div>
    </article> 
  </div>



  <!-- Section Information -->
  <div className="d-flex">
    <section>
      <h1>Information</h1>
      <div className="information-list">
        <ul className="list-option">
          <li>Location</li>
          <li>Experience</li>
          <li>Availability</li>
        </ul>
        <ul>
          <li>Tunisia</li>
          <li>2+ years</li>
          <li>1 week</li>
        </ul>
      </div>
    </section>

     <article className="mt-1">
      <h1>Resume</h1>
      <p>I'm a Creative Director and Designer from Tunis, Tunisia. I specialize in web development and print media. I enjoy turning complex problems into simple, beautiful, and intuitive designs.</p>
      <p>My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way. I've created web designs for many famous brand companies that you can refer to in my portfolio.</p>
      <div className="articleFooter">
        <p><a href="https://crocode-portfolio.surge.sh/">@Crocode</a></p>
        <div className="articleFooterImg">
          <ul>
            <li><a href="https://github.com/CrocodileCode">
            <img src="./assets/github.png" alt="github">
          </a> </li>
          <li><a href="https://www.instagram.com/aziz__saidi_">
            <img src="./assets/instagram.png" alt="instagram">
          </a> </li>
          </ul>
        </div>
      </div>
    </article> 
  </div>


  <!-- Skills Section -->
  <div className="d-flex">
    <section className="mt-1">
      <h1>Skills</h1>
      <div className="skills-list">
        <ul className="skills-option">
          <li>JavaScript</li>
          <li>Vue.js</li>
          <li>JQuery</li>
        </ul>
        <ul className="skills-option">
          <li>Css</li>
          <li>Bootstrap</li>
          <li>PHP</li>
        </ul>
        <ul className="skills-option">
          <li>Mysql</li>
          <li>HTML</li>
        </ul>
      </div>
    </section>

      <article className="mt-1">
      <h1>Education</h1>
      <p>I'm a Creative Director and Designer from Tunis, Tunisia. I specialize in web development and print media. I enjoy turning complex problems into simple, beautiful, and intuitive designs.</p>
      <p>My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add personal touch to your product and make sure that it is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way. I've created web designs for many famous brand companies that you can refer to in my portfolio.</p>
      <div className="articleFooter">
        <p><a href="https://crocode-portfolio.surge.sh/">@Crocode</a></p>
        <div className="articleFooterImg">
          <ul>
            <li><a href="https://github.com/CrocodileCode">
            <img src="./assets/github.png" alt="github">
          </a> </li>
          <li><a href="https://www.instagram.com/aziz__saidi_">
            <img src="./assets/instagram.png" alt="instagram">
          </a> </li>
          </ul>
        </div>
      </div>
    </article> 
  </div>


</template>

<style scoped>

header {
    border-radius: 15px;
    position: relative;
    width: 20rem;
    height: 22rem;
    padding: 0.6rem;
    display: flex;
    border: 1px solid rgba(201, 199, 199, 0.679);
    background-color: #fff;
    flex-direction: column;
    align-items: stretch;
    -webkit-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    -moz-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
}

header .profile-image{
    width: 8rem; 
    top: 7.7rem;
    border-radius: 15px;
    left: 1.3rem;
    position: absolute;
    -webkit-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    -moz-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    border: 3px solid white;
}

header .profile-banner{
   border-radius: 15px;
    width: 20rem;
    height: 10rem;
    -webkit-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    -moz-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    border: none;
}

header .profile-detail{
  padding-top: 2.5rem;
  padding-left: 1rem;
  padding-bottom: 1rem;
}

header .profile-detail span{
  color: rgb(153, 150, 150);
}

/* Article */
article{
    border-radius: 15px;
    position: relative;
    width: 37rem;
    padding: 0.6rem;
    display: flex;
    border: 1px solid rgba(201, 199, 199, 0.679);
    background-color: #fff;
    flex-direction: column;
    align-items: stretch;
    -webkit-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    -moz-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
}

article h1{
  padding: 15px;
  font-weight: 400;
}

article p{
  padding-bottom: 0;
  padding-top: 0;
  margin-top: 0;
  margin-bottom: 0;
  padding: 15px;
  font-weight: 400;
  color: #737882;
}

article p a{
  padding-bottom: 0;
  padding-top: 0;
  margin-top: 0;
  margin-bottom: 0;
  font-weight: 400;
  font-size: 18px;
  text-decoration: none;
  color: rgba(0, 128, 0, 0.837);
}

article .articleFooter{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

article .articleFooter .articleFooterImg ul{
  display: flex;
  padding-right: 5px;
  list-style-type: none;
}

article .articleFooter .articleFooterImg ul li{
  padding-right: 10px;
}

article .articleFooter .articleFooterImg img{
  width: 1.6rem;
}



/* Section Info  */

section{
    border-radius: 15px;
    position: relative;
    width: 20rem;
    margin-top: -1.5rem;
    padding: 0.6rem;
    display: flex;
    border: 1px solid rgba(201, 199, 199, 0.679);
    background-color: #fff;
    flex-direction: column;
    align-items: stretch;
    -webkit-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    -moz-box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
    box-shadow: 0px 3px 11px -7px rgba(0,0,0,0.75);
}

section h1{
  padding: 15px;
  font-weight: 400;
}

section .information-list{
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    align-items: center;
}

section .information-list ul{
  padding: 0;
  list-style-type: none;
}

section .information-list ul  li{
  padding: 15px;
}

section .information-list .list-option{
  color: #737882;
}

/* Skills Section */

section .skills-list{
    display: block;
    align-items: center;
}

section .skills-list ul{
  padding: 0;
  display: flex;
  flex-direction: row !important;
  list-style-type: none;
}

section .skills-list  li{
  background: rgba(0, 128, 0, 0.837);
  border-radius: 15px;
  padding: 15px;
  margin-left: 15px;
}

section .skills-list .skills-option{
  color: #eaeff7;
  border-radius: 5px;
}

</style>
