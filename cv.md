![Image](https://i.ibb.co/jkGhBTp/IMG-2772.jpg)
# Bohdan Rud
## Frontend Developer
---
## Contacts:
* *tel: 380955067089*
* *email: bogdan2516@gmail.com*
* *discord: Bohdan Rud (@Bogdan252525)*
---
## Summary
I am a Frontend Developer with a background in piano performance. I worked on cruise ships before transitioning to the tech industry, a field that has always fascinated me. I have completed several courses in frontend development and am currently practicing and seeking a position as a Frontend Developer. I am open to relocation and remote work opportunities.
---
## Skills
* JavaScript
* React.js
* Redux toolkit
* HTML5
* CSS3
* Tailwind
* GitHub
* npm
* VS Code
* Logical thinking
* Creativity
* Communication skills
* Self-discipline
* Self-control
---
## Code examples
You probably know the "like" system from Facebook and other pages. People can "like" blog posts, pictures or other items. We want to create the text that should be displayed next to such an item.

Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:
```
[]                                -->  "no one likes this"
["Peter"]                         -->  "Peter likes this"
["Jacob", "Alex"]                 -->  "Jacob and Alex like this"
["Max", "John", "Mark"]           -->  "Max, John and Mark like this"
["Alex", "Jacob", "Mark", "Max"]  -->  "Alex, Jacob and 2 others like this"
```
Note: For 4 or more names, the number in 'and 2 others' simply increases.

```
function likes(names) {
  names = names || [];
  switch(names.length){
    case 0: return 'no one likes this'; break;
    case 1: return names[0] + ' likes this'; break;
    case 2: return names[0] + ' and ' + names[1] + ' like this'; break;
    case 3: return names[0] + ', ' + names[1] + ' and ' + names[2] + ' like this'; break;
    default: return names[0] + ', ' + names[1] + ' and ' + (names.length - 2) + ' others like this';
  }
}
```
---