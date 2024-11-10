# DENIS ZHURAVLEV
**Phone:** +37529 569-85-22  
**Email:** <denisminskby@gmail.com>  
**Skype:** denisminskby  
**Linkedin:** <https://www.linkedin.com/in/denis-zhuravlev-b1621180>
## Summary
The main reasons for studying programming and looking for a new job are the desire to change the sphere of activity, the desire to constantly develop, learn something new and have a high level of income.

I am a highly organized, efficient and proactive. I believe that my ability to learn will allow me to quickly master the knowledge necessary in my work. My experience as a manager will allow me to competently organize the work process and lead a team in the future.
## Skills  
* Programming language: Java Script
* Front-end technologies: HTML5, CSS3
* Design pattern: MVC, SPA
* Framework: Bootstrap, React
* Databases: Firebase, Firestore
* Code version control: GIT

## Code example
[Task](https://leetcode.com/problems/rotate-array/description/): *Given an integer array nums, rotate the array to the right by k steps, where k is non-negative.*
```javascript
function rotate(nums: number[], k: number): void { 
  while (k > 0) {
    const lastElem = nums[nums.length - 1];

    for (let i = nums.length - 1; i > 0; i--) {
      nums[i] = nums[i - 1];
    }

    nums[0] = lastElem;
    k--;
  }
}
```

## Work experience  
**Nov 2020 - Mar 2021 – Educational Center for Programming and High Tech (IT-Academy)**  
**Project role:** Front-end Developer.  
**Project description:** Cross-browser web application, game *Zombie Hunter*.  
**Used tools:** App has been developed using the following stack of technologies: JavaScript, HTML, CSS, AJAX, Firebase. App is built on the principle of single-page application. Application code has been created with MVC architectural design pattern.  
**Link:** [Zombie Hunter](https://dns147.github.io/)

