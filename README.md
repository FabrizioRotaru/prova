<!DOCTYPE html>
<html>
  <head>
    <title>My HTML Page</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <div class="container">
      <h1>Welcome to my HTML page</h1>
      <p>This is a paragraph of text.</p>
      <button onclick="alertMessage()">Click me</button>
    </div>
    
    <script src="script.js"></script>
  </body>
</html>
*javascript
function alertMessage() {
  alert('Hello, world!');
}
*css
body {
  background-color: #f5f5f5;
}

h1 {
  color: blue;
  font-size: 36px;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

button {
  background-color: green;
  color: white;
  padding: 10px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}





