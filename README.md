# fizzBuzz-1-
This is slightly more difficult version of the famous FizzBuzz problem which sometimes given as a first problem for job interviews. Consider the series of numbers beginning at 'start' and running up to but not including 'end'. So, for example, start = 1 and end = 5 gives the series 1,2,3,4. Return a new String[] array containing the string form of these numbers, except that for multiples of of  3, use 'Fizz', for multiples of 5, use 'Buzz' and for multiples of both 3 and 5, use 'FizzBuzz'. 

/*ANSWER*/

function FizzBuzz(start, end){
for (i = start; i < end; i++){
if (i % 3 == 0 && i % 5 == 0){
 output.push('FizzBuzz') 
  }
else if (i % 3 == 0){
output.push('Fizz')
  }
else if (i % 5 == 0){
output.push('Buzz')
  }
else {
output.push(i)
  }
 }
}
const output =[];
FizzBuzz(2,24)
console.log(output);
