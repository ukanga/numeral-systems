# NUMERAL SYSTEMS - converts numbers by numerals system types ..
---
![imed-jaberi](/lib/images/logo.png) 

#### The purpose of this module is to convert any type of numbers to other type you want ..  

###### **`NOTE:`** you can send to me for add other type in [instgram](https://www.instagram.com/3imed_jaberi/) ..

## Installation 
---

- NPM :
```bash
$ npm install numeral-systems
```

## Usage 
---
The method of use is simple and very easy ... Just follow these steps :
Step 1 : Import the module in this way .
```javascript
const NS = require ('numeral-systems') ;
```
Step 2 : Enter the number to the function with the type of result number you want .
```javascript
let number  = "2019" ;
let typeResultNumerals = "Arabic";
let result = NS ( number , typeResultNumerals ) ;
console.log(`*******\n ${result} \n*******`);
```
Step 3 : Execute method to see the result ..
```bash
$your_pc_name_with_your_directory
*******
 ۲۰۱۹
*******
```
#### **`NOTE:`** in case the number is a modern type , you can enter the number to the function in number type .. so the step 2 will be : 

```javascript
let number  = 2019 ; 
let typeResultNumerals = "Arabic";
let result = ( number , typeResultNumerals ) ;
console.log(`*******\n ${result} \n*******`);
```

## Some Informations : 
---
In this module we have 4 numerals systems. You can convert between them  .. 
 - Modern : 1 , 2 , 3  4 , 5 , 6 , 7 , 8 , 9 , 10 ...
 - Arabic : ٠ , ١ , ٢ , ٣ , ٤ , ٥ , ٦ , ٧ , ٨ , ٩ , ١٠  ...
 - Persian : ٠ , ١ , ٢ , ٣ ,۴, ۵ , ۶ , ٧ , ٨ , ٩ , ١٠ ...
 - Romain ( Romain IN [ 1 .. 3999] ) : I , II , III , IV , V , VI , VII , VIII , IX , X  ... 

**`NOTE:`** Al-Khwarizmi put the modern numeral system for that is considered the original Arabic and this for the scientific secretariat, but we relied on the Arabic numerals very old under the name "Arabic" and the numerls  system developed by Al-Khwarizmi "modern" ...

#### License
---
[MIT](https://choosealicense.com/licenses/mit/) 

