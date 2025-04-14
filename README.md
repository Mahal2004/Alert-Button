# Alert-Button

<!DOCTYPE html>
Declares the document type and version of HTML being used. <!DOCTYPE html> specifies HTML5.

html
Copy
Edit
<html lang="en">
Starts the HTML document.

lang="en" tells the browser and search engines that the language of the content is English.

html
Copy
Edit
<head>
Begins the <head> section, which contains metadata and resources for the webpage (like styles, scripts, title, etc.).

html
Copy
Edit
    <meta charset="UTF-8">
Sets the character encoding to UTF-8, which supports most characters from all languages (important for internationalization).

html
Copy
Edit
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
Makes the page responsive.

width=device-width sets the width of the page to follow the screen-width of the device.

initial-scale=1.0 sets the initial zoom level when the page is first loaded.

html
Copy
Edit
    <title>Alert Button</title>
Sets the title of the webpage, which appears in the browser tab.

html
Copy
Edit
</head>
Ends the <head> section.

html
Copy
Edit
<body>
Begins the visible content of the HTML page.

html
Copy
Edit
    <button onclick="showAlert()">Click Me</button>
Adds a clickable button to the page.

When clicked, it triggers the showAlert() function using the onclick event.

html
Copy
Edit
    <script>
Begins a script block for JavaScript code.

javascript
Copy
Edit
        function showAlert() {
            alert("Hello! You clicked the button.");
        }
Defines the showAlert function.

When called, it uses alert() to display a popup message: "Hello! You clicked the button.".

html
Copy
Edit
    </script>
Ends the JavaScript section.

html
Copy
Edit
</body>
Ends the content body of the page.

html
Copy
Edit
</html>
Closes the HTML document.
