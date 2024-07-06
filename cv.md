# My CV 
 
## Khmialkov Ilya 
--- 
 
![My picture](img.jpg)
 
--- 
 
## Contacts 
- Telegram  @ilyakhmialkov 
- Github    @IlyaKhmialkov 
- Gmail     ilyakhmilakov@gmail.com 
- Discord   ilya_khmialkov 
 
--- 
 
## About me 
- i'm a student 
- my goal is to improve my front-end development skills 
- i can quickly absorb new information 
 
--- 
 
## Skills 
- C# 
- HTML 
- CSS 
- JavaScript 
- GitHub 
- Node.js 
 
--- 
 
## Code example 

```javascript
 
function toCamelCase(str){ 
  if(!str.includes('-') && !str.includes('_')){ 
    return str; 
  } 
  let words; 
  if(str.includes('-')){ 
    words = str.split('-'); 
  } else{ 
    words = str.split('_'); 
  }   
  for(let i = 0; i < words.length; i++){ 
    if(i != 0){ 
      words[i] = words[i].charAt(0).toUpperCase() + words[i].slice(1); 
    } 
  } 
  if(str.includes('_')){ 
    const newStr =  words.join(''); 
    let newWords = newStr.split('_'); 
    for(let i = 0; i < newWords.length; i++){ 
      if(i != 0){ 
        newWords[i] = newWords[i].charAt(0).toUpperCase() + newWords[i].slice(1); 
      } 
    } 
    return newWords.join(''); 
  } else{ 
    return words.join(''); 
  } 
} 
  
```

--- 
 
## Projects 
- card game (html, css, js) https://github.com/IlyaKhmialkov/card-game.github.io 
- course project - site of company (html, css, js, figma) https://github.com/IlyaKhmialkov/second-course-project 
 
--- 
 
## Education 
- Belarusian Russian University 2nd course 
 
--- 
 
## English proficiency level 
- A2