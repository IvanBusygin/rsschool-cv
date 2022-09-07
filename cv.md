# Ivan Busygin
## Junior Frontend Developer

---

### Contact information:

**Phone:** +7 917 288 14 63<br>
**E-mail:** bi-25@yandex.ru<br>

---

### Skills and Proficiency:

- HTML5, CSS3, JavaScript
- SCSS, BEM
- Git, GitHub, 
- Webpack, Vite, ESLint, Jest
- Vue3
- WebStorm, IntelliJ IDEA
- Adobe Photoshop, Illustrator, Figma

---

### Courses:

- Курс "JavaScript/DOM/Интерфейсы" [learn.javascript.ru](https://learn.javascript.ru/courses/jsbasic) (completed)<br>
- JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/) (completed)
- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

---

### Languages:

- Russian \- Native
- English \- Pre-intermediate<br>

---
### Code example:
**Common denominators. from CODEWARS**
```javascript
function convertFrac(lst) {
    const arrDenom1 = lst.map(item => item[1])
    let isInteger
    let den = Math.max(...arrDenom1)
    do {
        isInteger = arrDenom1.reduce((pre, item) => pre && (Number.isInteger(den / item)), true)
        if (!isInteger) den++
    } while (!isInteger)
    return lst.map(item => {
        let str1 = item[0] * (den / item[1])
        let str2 = item[1] * (den / item[1])
        return `(${str1},${str2})`
    }).join('')
}
```
#### example:
| input                      |        output        |
|----------------------------|:--------------------:|
| [ [1, 2], [1, 3], [1, 4] ] | "(6,12)(4,12)(3,12)" |

---

### Projects

- Ресторан с онлайн-заказом ["Bangkok Express"](https://course-jsbasic.javascript.ru/).

