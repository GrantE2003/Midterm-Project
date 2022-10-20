-[ Home](readMe.md)
-[ About Me](myInformation.md)
-[ My Education](myEducation.md)
-[ My Passions ](myHobbies.md)-

# **Previous Work**

I have experience writing in JavaScipt and Python 3. Here is my code and output for a project I did in JavaScript.

### Code:
    if (i%5 === 0 && i%3 === 0){
			displayHTML += "<p>" + 'FizzBuzz' + "</p>";
		} else if (i%3 === 0){
			displayHTML += "<p>" + 'Fizz' + "</p>";
		} else if (i%5 === 0){
			displayHTML += "<p>" + 'Buzz' + "</p>";
		} else{
			displayHTML += "<p>" + i + "</p>";
		}
	}

### Output:

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>
function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i <= 100; i++) {
		if (i%5 === 0 && i%3 === 0){
			displayHTML += "<p>" + 'FizzBuzz' + "</p>";
		} else if (i%3 === 0){
			displayHTML += "<p>" + 'Fizz' + "</p>";
		} else if (i%5 === 0){
			displayHTML += "<p>" + 'Buzz' + "</p>";
		} else{
			displayHTML += "<p>" + i + "</p>";
		}
	}
	display.innerHTML = displayHTML
}
</script>
</head>
<body onload="fizzbuzz()">
<div id="display">
</div>
</body>
</html>

