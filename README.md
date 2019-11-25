# My-HomeWork2
let arr = [1, 3, 2, 4, 10, 13, 32];
let a = 0;
for(let i = 0; i < arr.length; i++) {
  a += arr[i];
  if(a > 10) {
    console.log(i + 1);
    break;
  }
}