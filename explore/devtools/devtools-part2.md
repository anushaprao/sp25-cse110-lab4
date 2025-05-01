1. The bug was that the type of num1 and num2 are strings, so when they are concatenated, they are added as strings rather than integers. For example, for num1 equals 2, and num2 equals 3, the output is '23' instead of 5. 

Fix:
function calculateSum(num1, num2) {
  let result = Number(num1) + Number(num2);
  return result;
}
