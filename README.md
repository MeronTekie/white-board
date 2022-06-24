// question number one

//languages that I can use 
    java script
// excepted inputs
    just words
//input and expected output

 sentence =  

function noSpace(sentence){
  let newSentence ="";
  let  array = sentence.split(" ");
  for(i=0;i < array.length ; i++){
    newSentence +=array[i].concat("%20") 
  }
  return newSentence;
}
noSpace("Jasmine Ann Jones");


// prompt number two without recursion

clarify the question
exception handling
language preference
inputs
expected out put


function noReapetedValueOfAnArray(input){
  let newArray =[];
  for(i=0; i < input.length ;i++){
      if(!newArray.includes(input[i])){
        newArray.push(input[i]);
      }
    }
  
  return newArray;
}
noReapetedValueOfAnArray([7, 9, "hi", 12, "hi", 7, 53]);

prompt #3
clarify the question
exception handling
language preference
inputs
expected out put




prompt #4 

clarify the question
exception handling
language preference
inputs
expected out put

function booleanCheck(input){
  for(i=0;i < input.length;i++){
    for(j=i+1;j < input.length;j++)
    if( input[i]==input[j]){
      return true;
    }else{
      return false;
    }
  }
}
  booleanCheck();


// Prompt 5

sort an array 
function sortArray(array){
  for (let i = 0; i < array. length; i++) {
   for (let j = i + 1; j < array. length; j++) {
     if(array[i]>array[j]){
       temporary = array[i];
       array[i] =array[j];
       array[j]= temporary;
     }
    }
  }
  return array;
}
