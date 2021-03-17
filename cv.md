# [rsschool-cv](https://elisses.github.io/rsschool-cv/cv)
## Elis Fernanda A. S. Vieira
### Contacts Info

Email: fernandalisses@gmail.com

Phone: +48 573 328 207

Telegram: [Elis Fernanda](@ElisFernandaAgape)

Linkedin: [Elis Vieira](https://www.linkedin.com/in/elisfernanda)


### Summary

I  worked for 10 months as an Intern Java developer in Rio de Janeiro and I love to do this.I had a some experience with react js, Javascript, node js, HTML5 and CSS in a project e commerce for 6 month as junior developer volunteer. I learned how I needed to work with coworkers and suport them. I'm fascinated to study javascript, Angularjs and reactjs, so I would like to get a job as frontend developer.
I see oportunity to improve my skills and develop my knowledge. I would like to collaborate with the company with my knowledge and support my coworkers.

### Skill

| LANGUAGES | FRAMEWORKS | METHODOLOGIES | VERSION CONTROL
| --------- | ---------- | ------------- | --------------|
 Html | Css | SOLID patterns | Git / Github
 Javascript (intermediate) | Angular (Beginner) / React (intermediate) |Clean Code / Scrum | Visual Studio Code (intermediate)
 

### Code examples

* [Creative house](https://github.com/elisses/casaCriativa)

```
    <section id="buttons">
                <button onclick="onOff()"> + Adicionar Ideia</button>
                <button id='newIdea' class="fat">Ver Ideias</button>
            </section>

            <footer>
                Com ❤ <a href="https://github.com/elisses/">Elis Vieira</a>
            </footer>
```

* [Dino gamer](https://github.com/elisses/dino-game-dio)

```
let leftInterval = setInterval(() => {
        if (cactusPosition < -60) {
            clearInterval(leftInterval);
            background.removeChild(cactus);
        } else if (cactusPosition > 0 && cactusPosition < 60 && position < 60) {
            //Game Over
            clearInterval(leftInterval);
            document.body.innerHTML =
                "<div class= 'container'>" +
                "<div>" +
                "<img src='https://thumbs.gfycat.com/ShowyWaterloggedBichonfrise-small.gif' alt='game over'" +
                "</div>" +
                "<div class ='button-start'>" +
                "<button onclick='window.location.reload()'>Jogar Novamente</button>" +
                "</div>" +
                "</div>"
                ;

        } else {
            cactusPosition -= 10;
            cactus.style.left = cactusPosition + 'px';
        }
    }, 20);
```

[simple weather](https://github.com/elisses/simple-weather)
```
import axios from 'axios'

const URL = 'https://api.openweathermap.org/data/2.5/weather';
const API_KEY = 'd6ea0af9004e810578cc0b07718cc8ee';

export const fetchWeather = async (query) => {
    const { data } = await axios.get(URL, {
        params: {
            q: query,
            units: 'metric',
            APPID: API_KEY,
        }
    });

    return data;
}
```

### Experience

[Codewars](https://www.codewars.com/users/fernandalisses/)

I did some projects in my spare time to get experience. I put these projects on my github. I have motivation to program and all dedication in colaborated with good codes, solving problems and suporting the team. 

### Education

* RS School course of Frontend 2020

* Freecodecamp (in progress)

* Udemy Course react.js Ninja

* Digital Inovation Onne course javascript

### English

I started learning English at Archer School in Octuber of the 2018 and stopped in 2019 and changed for individual class for 1 year. I try to learn by reading books in English, practice writing and to go at meeting and make new friends for practise my English. I'm doing an English course on the English live platform.
