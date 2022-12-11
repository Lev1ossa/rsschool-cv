# Alexander Korobeynikov
## Junior Frontend Developer
## Contact information:
**Phone:** +7(903)098-10-20    
**E-mail:** ikehhui@gmail.com  
**Telegram:** @Lev1ossa  
**Discord:** Alex(@Lev1ossa)  
## About myself
Have started my career as 1C developer 3 years ago. A year ago, for the purpose of self-development, i began to study html/css and simple JS. And started to use it in main work progress. I enjoyed it and decided to learn more of js. Now i'm a student of RSSchool.
## Skills
1C (middle)  
HTML5, CSS3 (Basics)  
JavaScript (Basics)
Git, GitHub  
VS Code
## Code example
[Task on codewards](https://www.codewars.com/kata/54b72c16cd7f5154e9000457)
```var decodeBits = function(bits){
    if(bits[0] == 0 && bits[bits.length - 1] == 0){
      bits = bits.slice(1,-1);
    }
    const arr = bits.match(/0+|1+/g);
    let unitLong = [...arr].sort((a,b) => a.length - b.length)[0].length;
    let morseCode = arr.map(item => {
      if(item[0] == 0){
        if(item.length == unitLong * 7){
          return '  ';
        } else if(item.length == unitLong * 3){
          return ' ';
        } else {
          return '';
        }
      } else {
        if(item.length > unitLong){
          return '-';           
        } else {
          return '.';
        }
      }
    }).join('');
    return morseCode;
}

var decodeMorse = function(morseCode){
    return morseCode.split(' ').map((item) => item ? MORSE_CODE[item] : ' ').join('').trim();
}
```
## Work experience
1C developer from May 2019 to May 2022
## Education
self-studing (freecodecamp.org, learn.javascript.ru)
## Languages
Russian - native
English - pre-intermediate
