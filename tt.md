<input id="numb">

<button type="button" onclick="myFunction()">Submit</button>

<p id="demo"></p>

<script>
function myFunction() {
  var x, text;

  // Get the value of the input field with id="numb"
  x = document.getElementById("numb").value;
  window.location.href=x+".md"
  document.getElementById("demo").innerHTML = x+".md";
}
</script>
