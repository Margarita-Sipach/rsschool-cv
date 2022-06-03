# Margarita Sipach
***Junior Frontend Developer***
## Contacts
* **Phone** +375-29-366-26-33
* **Email** margarita.sipach@gmail.com
* **Github** [Margarita-Sipach](адрес "https://github.com/Margarita-Sipach")
## Brief information about myself
> I graduated lyceum BNTU. Now I'm 20 years old and studying at the university BSUIR. Currently I develop my skills in Frontent Development.
## My skills and knowledge
* **Frontend**
    + HTML
    + CSS, SCSS
    + JavaScript
    + VS Code
    + Figma
* **Backend**
    + PHP
    + C++
    + SQL (MySql, MS Sql)
* **Other**
    + Git, GitHub
 ## Сode example
*Напишите однострочное решение, которое вычисляет сумму квадратных корней для всех чётных чисел целочисленного массива.*
```
console.log(
 // Входной массив
 [1, 4, 3, 0, 4, 5, 4]
   // Оставляем только чётные числа
   .filter(element => !(element % 2))
   // Считаем квадратный корень и записываем в аккумулятор
   .reduceRight((accumulator, element) => accumulator + Math.sqrt(element), 0)
); // 6
```