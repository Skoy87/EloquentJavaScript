# EloquentJavaScript
function isEven (n){
  if (n==0){
      return 'true'
    } else if (n==1) {
      return 'false'
    } else if (n<=0){
      n=Math.abs(n)
      return isEven(n)
    } else {
      n=n-2
      return isEven(n)
    }
}   

console.log(isEven(50));
// → true
console.log(isEven(75));
// → false
console.log(isEven(-2));
// → ??




//http://eloquentjavascript.net/03_functions.html

// Your code here.
//var u='dhnuen'
//console.log(u.charAt(2))
function countBs (a){
  var n=0
  var Bs=0
  for (var checkB = a.charAt(n); n<a.length; n++){
    console.log(n)
    if (checkB = 'B'){
      Bs++}
    } return Bs+'0'
} 

console.log(countBs("BBC"));
// → 2
//console.log(countChar("kakkerlak", "k"));
// → 4
