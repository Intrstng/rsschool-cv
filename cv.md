[rsschool-cv](https://Intrstng.github.io/rsschool-cv/rsccool-cv "rsschool-cv")
====
# Andrei Babich
## Reach me at:
* **Location:** Minsk, Belarus
* **Phone:** +37529 255-98-34
* **E-mail:** Intrstg@gmail.com
* **GitHub:** [Intrstng](https://github.com/Intrstng "Intrstng")



## About Myself:
After starting my career as an engine mechanic, I became a lead engineer in a renewable energy company. My responsibilities included planning maintenance of equipment, calculating the cost of purchasing spare parts and conclusion of contracts with contractors, discussion and closing of warranty claims with foreign representatives of the equipment manufacturer.
The accumulated experience in my field allowed me to perform the tasks of a supervisor, I carried out quality control of the work performed by the staff, eliminated equipment malfunctions and trained the staff in the correct operation of the equipment. Teamwork helped me implement staff self-service of equipment and reduce equipment downtime and repair costs by 30%.

My previous experience was also related to computer diagnostics of electronic components of industrial engines and setting up and parameterizing controllers of automatic systems of these engines. Programming has always been enthralling me.
I am interested in web development because this field is developing rapidly, which gives the opportunity to constantly learn something new and improve professional level.
I believe that my focus on results and responsibility will help me become a Front-end developer and enter a society that strives for skill growth.

## Skills

* HTML5, CSS3, Sass/SCSS, BEM
* Javascript (Basic)
* Git, GitHub
* Adobe XD, Figma (for developers)

## Code Example
### Count strings in objects
Create a function strCount (takes an object as argument) that will count all string values inside an object. For example:
```
strCount({
  first: "1",
  second: "2",
  third: false,
  fourth: ["anytime",2,3,4],
  fifth:  null
  })
  //returns 3
```
##### Solution

```
function strCount (obj) {
let sum = 0

for (let key in obj) {
  if (typeof obj[key] === 'string' ) {
    sum += 1
  } if (typeof obj[key] === 'object') {
    sum += strCount(obj[key])
  }
}
return sum
}
```

## Courses
* UDEMY course - "Основы создания сайтов. HTML и CSS для начинающих (2019)"
* [freecodecamp.org](https://www.freecodecamp.org/ "freecodecamp.org")
* [CS50](https://www.youtube.com/channel/UCcabW7890RKJzL968QWEykA/ "CS50")
* JavaScript on [learnjavascript.ru](https://learn.javascript.ru/ "learnjavascript.ru")


## Education
* **University:** Belarusian National Technical University
*Technical Operation of Automobiles* - engineer-mechanic
* **College:** Minsk State Mechanical - Engineering College
 *Internal combustion engines* - 
 mechanical technician
----
## Languages
* English - Intermediate B1 + technical English ([efset.org](https://www.efset.org/quick-check/"efset.org") level 94% - Proficient)
* Russian - Native
* Polish - Basic