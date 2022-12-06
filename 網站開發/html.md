## HTML程式開發
```html
<!DOCTYPE html>
<html>
  
<head>
  <title>Welcome to Taiwan</title>
  <meta charset="UTF-8">
</head>  
  
<body>

<h1>My Dear Friends哈</h1>
<h1>My Dear small Friends哈</h1>

<p>This is mydeargreatteacher speaking</p>

</body>
</html>
```

## CSS
```html
<!DOCTYPE html>
<html>
<head>
<style> 
#rcorners1 {
  border-radius: 25px;
  background: #73AD21;
  padding: 20px; 
  width: 200px;
  height: 150px;  
}

#rcorners2 {
  border-radius: 25px;
  border: 2px solid #73AD21;
  padding: 20px; 
  width: 200px;
  height: 150px;  
}

#rcorners3 {
  border-radius: 25px;
  background: url(paper.gif);
  background-position: left top;
  background-repeat: repeat;
  padding: 20px; 
  width: 200px;
  height: 150px;  
}
</style>
</head>
<body>

<h1>The border-radius Property</h1>

<p>Rounded corners for an element with a specified background color:</p>
<p id="rcorners1">Rounded corners!</p>
<p>Rounded corners for an element with a border:</p>
<p id="rcorners2">Rounded corners!</p>
<p>Rounded corners for an element with a background image:</p>
<p id="rcorners3">Rounded corners!</p>

</body>
</html>
```

## Javascript
```html
<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Objects</h2>

<p id="demo"></p>

<script>
// Create an object:
const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};

// Display some data from the object:
document.getElementById("demo").innerHTML =
person.firstName + " is " + person.age + " years old.";
</script>

</body>
</html>
```
