# Abu-Bakar Musaev
### Junior Frontend Developer
---

### Contact information:
**E-mail:** xpox21@bk.ru<br>
**Telegram:** <b>[Web](https://t.me/web1developer)</b><br>
**[LinkedIn](https://www.linkedin.com/in/abu-bakar-musaev-b7a704216)**

---

### Briefly About Myself:

Working as a dental technician as a specialist, I did not find satisfaction in this profession.<br>
Looking for a hobby that would bring me pleasure, I stumbled upon html, css...<br>
So I started to dive into the field of web development,<br>
and now my life is code. I live in code and development.<br>

I know that my ability to learn and acquire new skills will help me become an experienced Frontend Developer.<br>

---

### Skills and Proficiency:

- HTML5, CSS3
- PUG, SASS/SCSS
- JavaScript, PHP, Java(basic)
- Vue JS, Laravel(basic)
- Git, GitHub
- Webpack, Vitejs
- VS Code, IntelliJ IDEA, PhpStorm
- Figma, Photoshop

---

### Code example:

**Peak array index KATA from CODEWARS:**
*Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```javascript
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
---

### Courses:

- JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/) 
- RS Schools Course «JavaScript/Front-end. Stage 1»

---

### Languages:

- English \- A1 <br>
- Germany \- B1 <br>
- Russian \- Native