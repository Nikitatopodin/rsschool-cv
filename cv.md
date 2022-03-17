# Nikita Bykovsky

## Contacts

* Location: Moscow, Russia
* Phone number: +7 915 405-54-46
* Email: nikitatop1@gmail.com
* Discord: Nikitatop1(@Nikitatopodin)

## About Me

Hey, there! My name is Nikita and I'm 25-years-old. I graduated from A.S. Griboedov Institute of International Law and Economics, majoring in linguist-translator. I'd worked as a freelance translator of movies and series subtitles for 3 months.

Now I have a full-time job. I work as an Audiovisual Translation Assistant. I don't actually translate anything at work, mostly, I transcribe Russian and English videos and audios, and create subtitles to videos in programms such as Adobe Affter Effects or Da Vinci Resolve. Sometimes I do some primitive video editing.

I find my job quite boring at the most of the times. And almost two months ago I've decided to try to become a frontend developer. My longterm goal is to become a fullstack developer but we'll see how it goes. May be because of the job I don't have that much time and energy for studying but I'll try my best.

## Skills

* HTML
* CSS
* JavaScript (Basics)

## Code Example

This is a code example of **Take a Ten Minute Walk** KATA from codewars with the following task: *You live in the city of Cartesia where all roads are laid out in a perfect grid. You arrived ten minutes too early to an appointment, so you decided to take the opportunity to go for a short walk. The city provides its citizens with a Walk Generating App on their phones -- everytime you press the button it sends you an array of one-letter strings representing directions to walk (eg. ['n', 's', 'w', 'e']). You always walk only a single block for each letter (direction) and you know it takes you one minute to traverse one city block, so create a function that will return true if the walk the app gives you will take you exactly ten minutes (you don't want to be early or late!) and will, of course, return you to your starting point. Return false otherwise.*:

```
function isValidWalk(walk) {
let array = []
  var result = walk.reduce(function(acc, el) {
  acc[el] = (acc[el] || 0) + 1;
  return acc;
}, [{}]);
  return walk[10] == undefined && walk[9] !== undefined && result.n == result.s && result.w == result.e
}
```
## Education 

* A.S. Griboedov Institute of International Law and Economics, linguist-traslator (2014-2019)
* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
* Self-studying (Youtube, Codewars, Codeacademy, Code-basics)

## Languages

* English – Advanced
* Russian – Native
* German – Basic 