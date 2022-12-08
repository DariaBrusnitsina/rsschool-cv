### Daria Brusnitsina
___
### Contacts:
- **Telegram:** @dariabru
- **E-mail:** dbrusnitsina@gmail.com
- **Discord:** Daria#5652
- **GitHub:** [DariaBrusnitsina](https://github.com/DariaBrusnitsina)
____
### About:
I graduated from the bachelor's and master's programs at the Faculty of Philosophy of Moscow State University. I like to learn and systematize knowledge, as well as get practical results from my work. Front-end development perfectly suits my requirements for the profession.
___
### Skills:
- HTML5
- CSS3 + SASS/SCSS, BEM, Bootstrap
- JavaScript
- React JS
- Webpack, Rollup
- Git, GitHub
- VScode, WebStorm, IDLE
- Python (basic knowledge)
- Figma (basic knowledge)
___
### Code example:
```
board.addEventListener("click", event => {
  const findThisPotion = document.querySelector(".potion-example")

  if (event.target.id === findThisPotion.id) {
    score++
    refreshScore()
    potions.sort(() => Math.random() - 0.5)
    board.innerHTML = ""
    createGameBoard()
    condition.innerHTML = ""
    createGameConditions()

  } else {
    const button = event.target.closest("img")
    
    if (button) {
      event.target.style.background = "rgba(178, 29, 17, 0.50)"
    }
   }
})
```
___
### Experiance:
- Game for a hackathon on pure JS [Potion game](https://github.com/DariaBrusnitsina/Potion-game)
___
### Education:
- **An Introduction to Python-Based Programming** (MSU training course)
- **Test drive of the Frontend developer profession** (Result School mini-course)
- **5 days 5 JavaScript projects** (Result School marathon)
___
### Languages:
- Russian – native
- **English – upper-intermediat**
