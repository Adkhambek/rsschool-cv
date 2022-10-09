# Adkhambek Muzaffarov

## Contact information

-   **Phone:** +998 998000334
-   **E-mail:** [muzaffarov.adham@gmail.com](mailto:muzaffarov.adham@gmail.com)
-   **Telegram:** [@Heaven_8](https://t.me/Heaven_8)
-   **LinkedIn:** [adham-muzaffarov](https://www.linkedin.com/in/adham-muzaffarov)
-   **GitHub:** [https://github.com/Adkhambek](https://github.com/Adkhambek)

## Summary

I am a full-stack web developer and enthusiast to progress within software development. My interests include making video tutorials, creating various web projects and many more. My main strengths are fast learning, problem solving and good communication skills.

## Skills

-   HTML
-   CSS (Bootstrap, SASS, BEM methodology)
-   JavaScript (Fundamentals, OOP, Asynchronous JavaScript, ES6+, TypeScript, DOM)
-   React JS (basic knowledge)
-   PHP (Laravel)
-   Node.js (Express, NestJS)
-   SQL: MySQL, PostgreSQL
-   NoSQL: Redis, MongoDB
-   Version control: git (remote service GitHub)

## Code examples

```js
// 1207. Unique Number of Occurrences
// https://leetcode.com/problems/unique-number-of-occurrences/

const uniqueOccurrences = function (arr) {
    const obj = {};
    for (const num of arr) {
        if (obj[num]) obj[num]++;
        else obj[num] = 1;
    }
    return (
        [...new Set(Object.values(obj))].length === Object.values(obj).length
    );
};

console.log(uniqueOccurrences([1, 2, 2, 1, 1, 3])); //t
console.log(uniqueOccurrences([1, 2])); // f
console.log(uniqueOccurrences([-3, 0, 1, -3, 1, 1, 1, -3, 10, 0])); // t
```

## Education

-   **Bachelor, INHA University in Tashkent**
    -   Faculty of Logistics
-   **Najot Ta'lim Education Center**
    -   Full-stack web development course
