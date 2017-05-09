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
