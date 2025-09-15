# Homecoming
<div class="stars"></div>

<h1>A long time ago, in a school not so far away...</h1>

<div class="crawl" id="crawlText">

<p>Episode HC</p>

<p>THE HOMECOMING AWAKENS</p>

<br>

<p>The galaxy is buzzing with excitement...</p>

<p>Rumors speak of an epic night filled with music, questionable dance moves, and maybe... lightsabers.</p>

<p>But no Jedi should go alone.</p>

<p>One brave padawan — Noah — must now face a destiny of great importance...</p>

<p>A friend has sent this message across the galaxy.</p>

<br>

<p>Noah, will you be their co-pilot for Homecoming?</p>

<p>They’ve chosen *you*. Yes, you.</p>

<br>

<p>This isn't a trap. (Definitely not set by the Empire.)</p>

<p>Just one friend asking another... to join the Rebellion (and dance).</p>

</div>

<div class="button-container" id="buttons">

<button onclick="playSaber(); alert('YAY! See you at the dance, co-pilot 🚀')">Yes</button>

<button onclick="playSaber(); alert('You had no choice anyway — it’s your destiny 💫')">Absolutely Yes</button>

</div>

<!-- Star Wars Theme Music -->

<audio id="themeMusic" autoplay loop>

<source src="https://cdn.pixabay.com/download/audio/2022/08/26/audio_2b7f4c9f13.mp3?filename=star-wars-theme-song-116973.mp3" type="audio/mpeg">

Your browser does not support the audio element.

</audio>

<!-- Lightsaber Sound -->

<audio id="saberSound">

<source src="https://cdn.pixabay.com/download/audio/2021/08/08/audio_78fc74c5ae.mp3?filename=lightsaber-on-14044.mp3" type="audio/mpeg">

</audio>

body {

margin: 0;

background: black;

color: yellow;

font-family: 'Arial', sans-serif;

overflow: hidden;

}

.stars {

background: url('https://i.imgur.com/O3Z4Ncm.png') repeat;

position: fixed;

width: 100%;

height: 100%;

z-index: -1;

background-size: cover;

}

.crawl {

position: absolute;

top: 100%;

width: 90%;

max-width: 700px;

left: 0;

right: 0;

margin: auto;

font-size: 20px;

text-align: center;

animation: crawl 40s linear forwards;

}

@keyframes crawl {

0% {

top: 100%;

transform: rotateX(20deg) translateZ(0);

}

100% {

top: -400%;

transform: rotateX(25deg) translateZ(-3000px);

}

}

.button-container {

position: fixed;

bottom: 50px;

left: 0;

right: 0;

text-align: center;

display: none;

}

button {

background-color: #ffe81f;

border: none;

color: black;

padding: 14px 28px;

margin: 10px;

font-size: 18px;

font-weight: bold;

border-radius: 8px;

cursor: pointer;

transition: 0.3s;

}

button:hover {

background-color: #fff76a;

}

h1 {

text-align: center;

color: white;

font-size: 1.8em;

margin-top: 20px;

padding: 0 10px;

}

@media (max-width: 500px) {

.crawl {

font-size: 16px;

}

button {

font-size: 16px;

padding: 12px 20px;

}

h1 {

font-size: 1.4em;

}

}

