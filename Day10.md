2/1/21

Orgainzed all of the post its from class with notes and things to look at.

Reasearched Code for America and signed up to work with them.

Code Wars - 25 mins
Make a function that can take any non-negative integer as a argument and return it with it's digits in descending order.
function descendingOrder(n){
  return parseInt(String(n).split('').sort().reverse().join(''))
}