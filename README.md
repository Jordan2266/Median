<!DOCTYPE html>
<html>
<head>

<button type="button" onclick= "myfunction()">Median</button>

<p id="Inputs"

<script>
function myfunction () {  
var Input1 = prompt ("Please enter first number");
var Input2 = prompt ("Please enter second number");
var Input3 = prompt ("Please enter third number");
var Input4 = prompt ("Please enter fourth number");
var Input5 = prompt ("Please enter fifth number");
    if (doc != null) { 
const median = arr => {
  const mid = Math.floor(arr.length / 2),
    nums = [...arr].sort((a, b) => a - b);
  return arr.length % 2 !== 0 ? nums[mid] : (nums[mid - 1] + nums[mid]) / 2;
};
console.log(median([Input1, Input2, Input3, Input4, Input5]));
  }
}
  
</script>


</head>
</html>
