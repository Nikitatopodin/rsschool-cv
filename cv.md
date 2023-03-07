# [rsschool-cv](https://nikitatopodin.github.io/rsschool-cv/cv)

# Nikita Bykovsky

## Contacts

* Location: Moscow, Russia
* Email: nikitatop1@gmail.com
* Discord: Nikitatop1(@Nikitatopodin)

## About Me

Hey, there! My name is Nikita and I'm 26-years-old. I graduated from A.S. Griboedov Institute of International Law and Economics, majoring in linguist-translator. 

I used to work as a freelance translator of movies and series subtitles for 3 months. After that I worked as an Assistant of Audiovisual translation department for more than a year. I didn't actually translate anything at work. Mostly, I transcribed Russian and English videos and audios, created subtitles to videos in programms such as Adobe Affter Effects or Da Vinci Resolve and checked tasks, which were done by others, for errors. Sometimes I did some primitive video editing. I also took part in some kind of Machine Translation research of the company.

I've tried to take RS Schools Course 'JavaScript/Front-end. Stage 1' back in a days, but haven't succeded. This time, I hope, I'll finish the course and learn lots of new coding stuff.

## Skills

* HTML
* CSS
* JavaScript (Basics)

## Code Example

This is a code example of **Luck check** KATA from codewars with the following task: *In some countries of former Soviet Union there was a belief about lucky tickets. A transport ticket of any sort was believed to posess luck if sum of digits on the left half of its number was equal to the sum of digits on the right half. Your task is to write a funtion luck_check(str), which returns true/True if argument is string decimal representation of a lucky ticket number, or false/False for all other numbers. It should throw errors for empty strings or strings which don't represent a decimal number.*

```
function luckCheck(ticket) {

  if (!/^\d+$/.test(ticket)) {
    throw new Error()
  }
  if (ticket.length % 2 == 0) {
    var arrOne = ticket.substring(0, ticket.length / 2).split('')
    var arrTwo = ticket.substring(ticket.length / 2, ticket.length + 1).split('')
  } else {
    var arrOne = ticket.substring(0, Math.floor(ticket.length / 2)).split('')
    var arrTwo = ticket.substring(Math.ceil(ticket.length / 2), ticket.length + 1).split('')
  }
  return arrOne.reduce((acc, elem) => +acc + +elem) == arrTwo.reduce((acc, elem) => +acc + +elem)
}
```
## Education 

* A.S. Griboedov Institute of International Law and Economics, linguist-translator (2014-2019)
* RS Schools Course 'JS/FE Pre-School 2022Q4'
* Self-studying

## Languages

* English - Advanced
* Russian - Native
* German - Basic