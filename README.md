Задачки

let arr2 = ["Kate", "Bob", "Jaden", "Max", "Angelina"] 

function numberNames(array){
let minName = array[0];
let maxName = array[0];
for(let i = 0; i < array.length; i++){
if(array[i].length < minName.length){
minName = array[i]
}
if(array[i].length > maxName.length){
maxName = array[i] 
}
}
return[minName,maxName]; 
}
console.log(numberNames(arr2));


