# Darya Zharskaya

### QA Engineer


## Contact Information:
**Email:** darya.zharskaya@gmail.com

**Telegram:** @darechka_z

**[Linkedin](https://www.linkedin.com/in/darya-zharskaya-205165166/)**

## Skills
* Understanding of SDLC and STLC
* Functional and non-functional testing basics
* Creation of test documents:
    - test plan
    - checklists
    - test cases
    - bug reports
    - test result report
* Test design techniques
* Web testing basics
    - client-server model
    - HTML5, CSS3
    - DevTools
    - Web form testing
* API testing basics (REST)
* SQL
* JavaScript basics
* Git, Github
* Tools:
    - Jira
    - TestRail
    - Postman
    - Charles Proxy
    - VSCode

## Languages
* **English** - Upper-Intermediate (B2)
* **Russian** - Native
* **Belarusian** - Native

## Courses
* **"JavaScript/Front-end. Stage 0"** course by RS School (in progress)
* **Software Testing** course by Vadim Ksendzov (in progress)
* **Functional Software Testing** course by IT Academy (November 2021 - February 2022, [certificate](https://drive.google.com/file/d/1SCO4zKaBIB_0YobPuOeeYTHz8ueHsPLO/view?usp=sharing))

## Education
**Belarusian State University**, 2005 - 2010

*Faculaty of International Relations*


## Code Example

**Task**
*Create ***evenFn(n)*** function that accepts a number as an argument. The argument (n) sets the number of loop iterations.The function must return an array consisting of even numbers that are generated in each iteration of the loop.*
***Note***
 * *0 (zero) must not be included in the resulting array*
 * *the loop must be executed till ***n*** times inclusive*
 * *only "for" loop can be used in this task*

```javascript
function evenFn(n) {
    let arr = [];
    for(let i = 0; i <= n; i++) {
        if(i%2 == 0 && i != 0) {
            arr.push(i);
        }
    }
    return arr;
}
console.log(evenFn(10)); // [2, 4, 6, 8, 10]
console.log(evenFn(15)); // [2, 4, 6, 8, 10, 12, 14]
console.log(evenFn(20)); // [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
```
