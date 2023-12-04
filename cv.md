# Misha Panchenko
### Contacts 
- GitHub - mishazpua
- email - mishazpua@gmail.com

### About Me
My goal is to become a backend developer. My strength is determination, reliability, perseverance. I have a desire to learn, I’m currently taking training courses and solving problems on Codewars.

### My Skills
JavaScript&HTML at a basic level
### Code Example
**Simple Pig Latin Kata from Codewars:**_Move the first letter of each word to the end of it, then add "ay" to the end of the word. Leave punctuation marks untouched._
```
function pigIt(str){
    let symbols = "!,./?";
    let postfix = "ay";
    return str.split(" ").map(function (word) {
        let tmp = "";
        for(let i = 0; i < symbols.length; i++){
            if(word !== symbols[i]){
                tmp = word.substring(1) + word[0] + postfix;
            }else{
                tmp = word.substring(1) + word[0];
                break;
            }
        }
        return tmp;
    }).join(" ");
}
```

### Education 
- School: I'm currently finishing high school. 
- Courses: I am currently taking a course at RS School.
### English
A2
