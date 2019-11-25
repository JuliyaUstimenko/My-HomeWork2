# My-HomeWork2
let n = prompt("Ввести длинну массива")
str = '';
arr = [];
for(let i = 1; i < n; i++) {
  for(let j = 1; j <= i; j++) {
    str += i
  }
  arr.push(str);
  str = '';
}
console.log(arr);