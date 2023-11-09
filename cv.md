# Mikita Kuzniatsou

### Contacts: 
* Phone: +48 516 589 963
* Email: nikitakuza1999@gmail.com
* [LinkedIn](https://www.linkedin.com/in/mikita-kuznetsov-37642a235/)
* [My GitHub](https://github.com/aggamix)

### About me:
In my little career experience I have managed to acquire good qualities. I am stress resilient, pressure resistant and good at multitasking. I always have a plan that I work on to maximize my day. I also have the quality:  Management of the team, responsible for others, training of the employees, respectful attitude to all, attentive, calm and of course I have a good sense of humor. All this experience I got for 3 years of work in different areas. For about a year, I’ve been studying frontend development. Now I’m taking a course where I’m consolidating and improving my knowledge to get a job and move forward in the technology world. This has almost become my job because I write code every day. I practice my knowledge in solving new problems. I always try to solve the problems I face in learning and in life.

### Skills: 
* HTML
* CSS
* JS
* React
* Git
* Figma
* VSCode

### Code example: 
[Stop gninnipS My sdroW!](https://www.codewars.com/kata/5264d2b162488dc400000001)

Write a function that takes in a string of one or more words, and returns the same string, but with all five or more letter words reversed (Just like the name of this Kata). Strings passed in will consist of only letters and spaces. Spaces will be included only when more than one word is present:
* `spinWords( "Hey fellow warriors" ) =>` returns "Hey wollef sroirraw".
* `spinWords( "This is a test") =>` returns "This is a test".
* `spinWords( "This is another test" =>)` returns "This is rehtona test".

```
function spinWords(string){
    let apart = string.split(" ");
    let str = [];

    for (let item of apart){
        if (item.length > 4){
            str.push(item.split("").reverse().join(""));
        } else {
            str.push(item);
        }
    }

    return str.join(" ");
}

console.log(spinWords("Hey fellow warriors"));
```
* [My Codewars](https://www.codewars.com/users/Aggamix)
* [My LeetCode](https://leetcode.com/aggamix/)
