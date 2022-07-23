//Smalles Number 

var smalestNumber= (arr)=>{
  var smallN=0;
  for(let i=0; i<arr.length; i++){
    if(smallN < arr[i]){
      smallN=arr[i]
    }
  }
  return smallN;
}
console.log(smalestNumber([1,2,3,4,5,6,-1,2,11]))

let arr = [1,2,3,4,5];

console.log("Min value of the array is", Math.min(...arr));
console.log("Max value of the array is", Math.max(...arr));


  var arr =[1,2,3,4,5,6]
  var sortE = (arr) => arr.sort((a,b) => b-a)[0]
 console.log(sortE(arr));
  

  
  var arr =[1,2,3,4,5,6]
  var sortE = (arr) => arr.reduce((a,b) => b>a ? b : a)
  console.log(sortE(arr));


  Sum Of the array

    var arr =[1,2,3,4,5,6]
  var sortE = (arr) => arr.reduce((a,b) => b+a )
 console.log(sortE(arr));

 
  var arr =[1,2,3,4,5,6]
  var sum = (arr) =>{
     var sum1=0;
    for(var ele in arr){
      
    sum1+=arr[ele];
    }
    
   return sum1;
  }
 console.log(sum(arr));
  