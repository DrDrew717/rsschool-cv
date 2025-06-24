# Andrei Ivanov
![Avatar](https://avatars.githubusercontent.com/u/211639598?s=192&v=4)

## Contact information
* **Location:** Bishkek, Kyrgyzstan
* **Phone:** +996224623662
* **Email:** andyak0717@gmail.com
* **Discord:** andyak0717(DrDrew717)

## Professional Summary
Environmental researcher with a background in sustainability and ecological data analysis. Currently developing skills in JavaScript, HTML, and CSS to create interactive tools and web-based platforms for science communication and public outreach.

## Education
* Kyrgyz National University<br>
*Master of Environmental Science, 2012–2014*<br>
* Kyrgyz Agrarian University<br>
*Bachelor of Ecology and Environmental Management, 2007–2011*<br>

## Professional Experience
* Institute of Ecology and Sustainable Development, Bishkek
*Research Associate, September 2014 – Present*

## Technical Skills
* MS Office, Excel, OriginLab, SPSS
* ArcGIS, QGIS
* Figma, Photoshop
* VS Code, Git

## Code Example
**["Dot Calculator"](https://www.codewars.com/kata/6071ef9cbe6ec400228d9531) task from CODEWARS:** *you have to write a calculator that receives strings for input. The dots will represent the number in the equation. There will be dots on one side, an operator, and dots again after the operator. The dots and the operator will be separated by one space.*

```
function dotCalculator(equation) {
    let result = '';
    let a = 0;
    let b = 0;
    let sum = 0;

    for (i = 0; equation[i] !== ' '; i++) a = a + 1;
  
    for (i = equation.length - 1; equation[i] !== ' '; i--) b = b + 1;

    for (i = 0; i < (a + 2); i++) {
      if (equation[i] === '+') {
        sum = a + b;
      } else if (equation[i] === '-') {
        sum = a - b;
      } else if (equation[i] === '*') {
        sum = a * b;
      } else if (equation[i] === '/') {
        sum = Math.floor(a / b);
      } else {
        sum = 0;
      }
    }

    result = '.'.repeat(sum);   
    return result;
  }
```

## Languages
* Russian - Native
* English - Intermediate

