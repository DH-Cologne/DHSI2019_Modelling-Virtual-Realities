# A short overview on how to develop a website

## HTML

### Structure of an HTML document

```
<!DOCTYPE html>

<html>
	
<head>
			<meta charset="utf-8">
			<title>Name of your HTML document</title>
	</head>


	<body>
		<!-- A comment -->
		Hello World!
	</body>

</html>
```

#### Exercise 1: Create a new text file index.html with the following content

```
<!DOCTYPE html>

<html>
	
<head>
			<meta charset="utf-8">
			<title>Name of the HTML document</title>
	</head>


	<body>
		<!-- A comment -->
		Hello World!
	</body>

</html>
```

Make sure that you have switched on the file name extensions under MS Windows!

- Call up your HTML document with a web browser of your choice. Which information is displayed in the title bar of the application, which information in the (white) page area?
- Change the "Name of your HTML document" in the header of the HTML document. Save the HTML file and update the website in your browser.
- Change the specification "Hello World!" in the body of the HTML document. Save the changed HTML file and update the website in your browser.

#### Exercise 2: Hands-on – Tags, Attributes, Syntax, Nesting, Well-formedness, Hyperlinks, Images, Tables

### Cascading Style Sheets

#### Exercise 1: Inline style definitions, Stylesheets

### JavaScript

####  Exercise 1: Add the following form to your website

```
<form>
    <label for="first">Number 1:</label>
    <input type="text" name="num1" id="first"><br>
    <label for="second">Number 2:</label>
    <input type="text" name="num2" id="second"><br>
    Sum: <span id="result"></span>
    <input type="button" value="Sum" onclick="calcSum()">
</form>
```

#### Exercise 2: Hands-on – Reading and writing DOM-element content 
