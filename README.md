# hello-world


let array = [94, 2, 71, 10, 22, 71] // Наименьшее число
function minNum(nums){
let min = nums[0];
for(let i = 0; i < nums.length; i++){
if(nums[i] < min){
min = nums[i];
}
}
return min;
}
console.log(minNum(array));


for(let i = 1000; i >=0; i = i - 5){  // Числа от 1000 до 0 с интервалом 5
console.log(i)
}


let i = 1000; // Числа от 1000 до 0 с интервалом 5
while(i > 0){
i = i - 5;
console.log(i);
}


let arr1 = ["Kate", "Bob", "Jaden", "Max", "Angelina"] // Слова не более 4 букв

function numberNames(arr,length){
const newArr = [];
for(let i = 0; i < arr.length; i++){
if(arr[i].length <= length) newArr.push(arr[i])
}
return newArr;
}
console.log(numberNames(arr1, 4));


let numbers = [1,2,3,4,5,6,7,8,9,10,11]  // Вывод не чётных чисел в массиве

function evenNumbers(arr){
 let result = [];
 for(let i = 0; i < arr.length; i++){
   if(arr[i] % 2 !==0){
     result.push(arr[i])
   }
 }
 return result;
}
console.log(evenNumbers(numbers));


let numbers2 = [1,2,3,4,5,6,7,8,9,10,11]  // Вывод чётных чисел в массиве

function evenNumbers(arr){
 let result = [];
 for(let i = 0; i < arr.length; i++){
   if(arr[i] % 2 ===0){
     result.push(arr[i])
   }
 }
 return result;
}
console.log(evenNumbers(numbers2));


let arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] // Сумма чисел в массиве

function sum(arr) {
  let result = 0;
  for(let i = 0; i < arr.length; i++) {
    result += arr[i];
  }
   return result;
}
console.log(sum(arr));


