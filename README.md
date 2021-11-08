# FreeCodeCamp3


 40  function sequentialSizes(val) {
  let answer = "";
  // Only change code below this line
switch(val){
  case 1:
  case 2:
  case 3:
    return "Low";
   break;
  case 4:
  case 6:
  case 5:
    return "Mid";
   break;
  case 7:
  case 8:
  case 9:
    return "High"
   break;
}



  // Only change code above this line
  return answer;
}

sequentialSizes(1);


31// Setup
const myArray = [["John", 23], ["dog", 3]];
 let removedFromMyArray = myArray.shift();
// Only change code below this line
!!!!!!!!!!!!



32 // Setup
const myArray = [["John", 23], ["dog", 3]];
myArray.shift();
myArray.unshift(["Paul", 35]);

// Only change code below this line

33 //const myList = [
  ['дыня', 1],
  ['хлеб', 2],
  ['сосиски', 3],
  ['макароны', 4],
  ['кирпичи', 5]
];

34  function reusableFunction(){
console.log("Hi World")

}

reusableFunction()


35  function functionWithArgs(arg1, arg2){

  console.log(arg1 + arg2)
};

functionWithArgs(1,4);

36  function timesFive(number){
  return number * 5;
}

let multiply = timesFive(2)


37 // Declare the myGlobal variable below this line


function fun1() {
  // Assign 5 to oopsGlobal Here
  oopsGlobal = 5;
}

// Only change code above this line
let myGlobal = 10

function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}



38 // Setup
const outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
let outerWear = "sweater"
  // Only change code above this line
  return outerWear;
}

myOutfit();
!!!!!!!!!!!!


39  function caseInSwitch(val) {
  let answer = "";
  // Only change code below this line
switch(val){
  case 1 : return "alpha";
  break;
  case 2 : return "beta";
  break;
  case 3 : return "gamma";
  break;
  case 4 : return "delta"
  

} 


  // Only change code above this line
  return answer;
}

caseInSwitch(1);
