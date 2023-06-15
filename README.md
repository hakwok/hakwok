![backdrop1](https://github.com/hakwok/hakwok/assets/77424165/e5bf779b-5b91-4d44-9eee-526969be1cec)
<h1 align="center">Hi 👋, I'm Hayden</h1>
<h3 align="center">Computer Science @ UC San Diego</h3>
```html
<style>
$grey: rgba(0, 0, 0, .5);
$blue: rgba(0, 0, 255, .5);

@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  50% {
    transform: rotate(180deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

@keyframes rotate2 {
  0% {
    transform: rotate(0deg);
    border-top-color: $grey;
  }
  50% {
    transform: rotate(180deg);
    border-top-color: $blue;
  }
  100% {
    transform: rotate(360deg);
    border-top-color: $grey;
  }
}

* {
  box-sizing: border-box;
}

body {
  background: #f9f9f9;
  padding-bottom: 100px;
}

h1, h3 {
  display: block;
  margin: 0px auto;
  text-align: center;
  font-family: 'Tahoma';
  font-weight: lighter;
  color: $grey;
  letter-spacing: 1.5px;
}

h1 {
  margin: 50px auto;
}

@mixin loaderDivMixin {
  border-radius: 50%;
  padding: 8px;
  border: 2px solid transparent;
  animation: rotate linear 3.5s infinite;
}

.loader {
  position: relative;
  margin: 75px auto;
  width: 150px;
  height: 150px;
  display: block;
  overflow: hidden;
  div {
    height: 100%;
  }
}

/* loader 1 */
.loader1, .loader1 div {
  @include loaderDivMixin;
  border-top-color: $grey;
  border-bottom-color: $blue;
}

/*loader 2  */
.loader2, .loader2 div {
  @include loaderDivMixin;
  border-top-color: $blue;
  border-left-color: $grey;
  border-right-color: $grey;
}

/*loader 3  */
.loader3, .loader3 div {
  @include loaderDivMixin;
  border-top-color: $grey;
  border-left-color: $blue;
  animation-timing-function: cubic-bezier(.55, .38, .21, .88);
  animation-duration: 3s;
}

/* loader 4 */
.loader4, .loader4 div {
  @include loaderDivMixin;
  border-radius: 50%;
  padding: 4px;
  animation: rotate2 4s infinite linear;
}

div:hover {
  animation-play-state: paused;
}

.loader, .loader * {
  will-change: transform;
}
</style>

<div class='loader loader1'>
  <div>
    <div>
      <div>
        <div>
          <div>
            <div></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class='loader loader2'>
  <div>
    <div>
      <div>
        <div>
          <div>
            <div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class='loader loader3'>
  <div>
    <div>
      <div>
        <div>
          <div>
            <div></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class='loader loader4'>
  <div>
    <div>
      <div>
        <div>
          <div>
            <div>
              <div>
                <div>
                  <div>
                    <div></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
  
- 🔭 I’m currently working on contributing to a **personalized TradingView Machine Learning Trading Algorithm**

- 🌱 I’m currently learning **React.js & React Native**

- 👨‍💻 My personal website and portfolio: [https://www.haydenkwok.com/](https://www.haydenkwok.com/)

- 📫 You can reach me at **hayden.kwok@gmail.com**

- ⚡ Fun fact: **I am studying to become fluent in 5 different languages**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/haydenkwok" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="haydenkwok" height="30" width="40" /></a>
<a href="https://instagram.com/ekw0k" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="ekw0k" height="30" width="40" /></a>
<a href="https://discord.gg/https://discord.gg/kMWpaTsM" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="https://discord.gg/kMWpaTsM" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://reactnative.dev/" target="_blank" rel="noreferrer"> <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> <a href="https://vuejs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/> </a> <a href="https://www.adobe.com/products/xd.html" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/adobe-xd.svg" alt="xd" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=hakwok&show_icons=true&locale=en&layout=compact" alt="hakwok" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=hakwok&show_icons=true&locale=en" alt="hakwok" /></p>
