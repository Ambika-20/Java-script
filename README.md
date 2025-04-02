# Unique-Number
#To identify unique number in an array using Javascript
let a = [10,10,20,30];
let unique = a.filter((item, i, ar) => ar.indexOf(item) === i);
console.log(unique);
