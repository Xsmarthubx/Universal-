
HTML:
```
<!DOCTYPE html>
<html>
<head>
	<title>Log In</title>
</head>
<body>
	<h1>Log In</h1>
	<form>
		<label for="username">Username:</label>
		<input type="text" id="username" name="username"><br><br>
		<label for="password">Password:</label>
		<input type="password" id="password" name="password"><br><br>
		<input type="submit" value="Log In">
	</form>
</body>
</html>
```
CSS:
```
body {
	background-color: #f2f2f2;
	font-family: Arial, sans-serif;
}

form {
	width: 300px;
	margin: 0 auto;
	padding: 20px;
	background-color: #fff;
	border: 1px solid #ddd;
	border-radius: 10px;
	box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

label {
	display: block;
	margin-bottom: 10px;
}

input[type="text"], input[type="password"] {
	width: 100%;
	height: 40px;
	margin-bottom: 20px;
	padding: 10px;
	border: 1px solid #ccc;
}

input[type="submit"] {
	background-color: #4CAF50;
	color: #fff;
	padding: 10px 20px;
	border: none;
	border-radius: 10px;
	cursor: pointer;
}

input[type="submit"]:hover {
	background-color: #3e8e41;
}
```
JavaScript:
```
// JavaScript code for form validation and submission
```
