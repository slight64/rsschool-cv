**1.** Vladimir Denisenko
***
**2.** Telegram: @slight64
***
**3.** My goal is to become a developer. Every day I devote time to code, master new technologies and consolidate them in practice. Doing well is a priority.
***
**4.** 

 * VS Code, WebStorm,
 * BEM, PUG, React, Git,
 * HTML, CSS, JS.
***
**5.**
```
function topThreeWords(text) {
  const wordsArray = text.match(/\w+'\w+|'\w+ |\w+'|\w+|'\w+'/g);
  if (!wordsArray) {
    return [];
  } else {
    const top = {};
    const lowerCase = wordsArray.map((el) => el.toLowerCase());
    lowerCase.forEach((el) => {
      if (top[el]) {
        top[el] += 1;
      } else {
        top[el] = 1;
      }
    });
    const newArr = [];
    for (i in top) {
      newArr.push([i, top[i]]);
    }

    const sorted = newArr.sort((a, b) => b[1] - a[1]);
    return sorted.map((el) => el[0]).slice(0, 3);
  }
}
```
### HTML CSS
[layout-01](https://github.com/slight64/layout-01)

### React
[swapi](https://github.com/slight64/swapi)
[TodoReact](https://github.com/slight64/TodoReact)

### JS
[pureJsWeatherApp](https://github.com/slight64/pureJsWeatherApp)
***
**6.** Without experience
***
**7.** higher education, lawyer

   * JavaScript 2021 - Полное Руководство с Нуля до Профи
   * JavaScript - Полный Курс По JavaScript
   * React - Полный Курс по React

***
**8.** INTERMEDIATE (B1)
   I use programs in English,
   I watch a lot of foreign videos.
***