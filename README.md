# hello-world


let array = [94, 2, 71, 10, 22, 71]
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


for(let i = 1000; i >=0; i = i - 5){
console.log(i)
}

let i = 1000;
while(i > 0){
i = i - 5;
console.log(i);
}

let arr1 = ["Kate", "Bob", "Jaden", "Max", "Angelina"] 

function numberNames(arr,length){
const newArr = [];
for(let i = 0; i < arr.length; i++){
if(arr[i].length <= length) newArr.push(arr[i])
}
return newArr;
}
console.log(numberNames(arr1, 4));



