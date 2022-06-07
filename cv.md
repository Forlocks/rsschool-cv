# Alexey Shelukhin

## Contact information
* **Phone number:** +79602865676
* **E-mail:** sheluhen@mail.ru
* **VKontakte:** @2forlock0
* **Telegram:** @forlocks
* **GitHub:** https://github.com/Forlocks
* **Nickname on the discord-server RS School:** Forlock (@Forlocks)

## About me
I am 20 years old, study at the Saint-Petersburg State University of Aerospace Instrumentation in the direction of "Laser equipment and laser technologies". At the beginning of his second year at the university, he became interested in the profession of a front-end developer, after which he began to take various free courses on the study of HTML, CSS and JS. I hope to gain more knowledge from the courses at RS School to become a junior front-end developer as a result.

## Skills
* Markdown
* HTML
* CSS (+Bootstrap)
* JS (basics)
* Git and GitHub
* VScode

## Code example
```
//Generate a random floating point number from min to max (but not including max).

"use strict";

let userNumber, firstNumber, secondNumber, min, max, difference, lucky, randomNumber, result;

function readNumber() {
userNumber = prompt('Enter number', '');

while (userNumber === "" || userNumber === null || Object.is( parseFloat(userNumber), NaN)) {
userNumber = prompt('Enter number', '');
}

return parseFloat(userNumber);
}

firstNumber = readNumber();
secondNumber = readNumber();

max = Math.max(firstNumber, secondNumber);
min = Math.min(firstNumber, secondNumber);

function random(min, max) {
if (min === max) {
alert('Error');

return NaN;
}

lucky = Math.random();
difference = max - min;
randomNumber = difference * lucky;
result = min + randomNumber;

return result;
}

alert( random(min, max) );
```

## Education
* Courses on the educational platform Stepik:
    * Web Development for Beginners: HTML and CSS (100% + Certificate)
    * JavaScript for Beginners (100% + Certificate)
* Learn.javascript (in the process)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in the process)

## Proficiency in English and other languages
* **English:** А2 (Elementary)
* **Russian:** 100%