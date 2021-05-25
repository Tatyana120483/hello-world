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
