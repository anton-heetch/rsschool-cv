# Anton Sokolov
![avatar](./images/avat.png)
#### *Frontend engineer*
***
### Contact info

* **Phone:** +7 (777)022-67-20
* **E-mail:** [green.frost@gmail.com](mailto://green.frost@gmail.com)
* **Telegram:** [@antonheetch](https://t-do.ru/@antonheetch)
* **Linked-in:** [anton-ht](www.linkedin.com/in/anton-ht)
---
### About
Engaged in the development of various types of projects. E-commerce, thematic community sites, promo sites, internal company service for holding and storing seminars. I was engaged in development both from scratch and developed individual modules and functionalities.

For the last year I have been working with the Vue2 + Nuxt2 stack, I am also familiar with Vue3 and Composition Api, Pinia.
I also have experience with React Redux.

Working with SSR, integration with backend via REST Api.
Optimizing the speed of work and loading sites.
Design principles SOLID, DRY, KISS, YAGNI.
Code refactoring.

I use architectural patterns and design principles in my projects. MVVM, MVC.

---
### Skills
![html5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![css](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![gulp](https://img.shields.io/badge/Gulp-CF4647?style=for-the-badge&logo=gulp&logoColor=white)
![webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white)
![vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vuejs](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Nuxtjs](https://img.shields.io/badge/nuxt.js-00C58E?style=for-the-badge&logo=nuxtdotjs&logoColor=white)
![Reactjs](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![figma](	https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![photoshop](https://img.shields.io/badge/Adobe%20Photoshop-31A8FF?style=for-the-badge&logo=Adobe%20Photoshop&logoColor=black)
---
### Code Examples
DESCRIPTION:
In this kata you have to correctly return who is the "survivor", ie: the last element of a Josephus permutation.
```
function josephusSurvivor(n,k){

  let counter = 0
  let index = 0
  let soldiers = [...Array(n).keys()].map(x => ++x)

  while (soldiers.length > 1) {
    index = index % soldiers.length
    
    if (++counter === k) {
      soldiers.splice(index, 1)[0]
      counter = 0
      index--
    }
    index++
  }
   return soldiers[0]
}
```
---
### Education
#### Kazakh-American University
Computer Science faculty

### Licenses & certifications
**[EFSET English Certificate 59/100 (B2 UPPER INTERMEDIATE)](https://www.efset.org/cert/PzREbT)**

### Courses
Online courses from Udemy
* [React Front To Back 2022](https://www.udemy.com/course/react-front-to-back-2022/) Brad Traversy

Free courses from [JavaScript.Ninja](https://www.youtube.com/c/JavascriptNinja)

---
### Languages
* **Russian** - native speaker
* **English** - B1 (B2 in process…)