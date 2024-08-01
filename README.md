            HTML AND CSS AND JS:
          HTML (HyperText Markup Language) and CSS (Cascading Style Sheets) are essential technologies for creating and designing web pages. JavaScript (JS) often complements these technologies to create dynamic and interactive web experiences. Here’s a detailed explanation of each and how they work together in projects:
          
          HTML (HyperText Markup Language)
          Purpose: HTML is the standard markup language used to create the structure of web pages.
          Elements: HTML consists of a series of elements represented by tags. Common tags include <div>, <p>, <a>, <img>, <h1> to <h6>, <ul>, and <li>.
          Attributes: Elements can have attributes that provide additional information. For example, the href attribute in the <a> tag specifies the URL of the link.
          Structure: HTML provides the skeleton of a web page, organizing content into a hierarchy of elements.
          CSS (Cascading Style Sheets)
          Purpose: CSS is used to style and layout web pages. It controls the visual presentation of HTML elements.
          Selectors: CSS uses selectors to target HTML elements. Common selectors include element selectors (div), class selectors (.className), and ID selectors (#idName).
          Properties: CSS defines a wide range of properties such as color, font-size, margin, padding, border, display, and position to style elements.
          Cascading and Inheritance: CSS allows styles to cascade from parent to child elements and supports inheritance of styles, making it easier to apply consistent styling across a website.
          JavaScript (JS)
          Purpose: JavaScript is a programming language used to create dynamic and interactive effects on web pages.
          DOM Manipulation: JavaScript can manipulate the Document Object Model (DOM), which represents the structure of an HTML document. This allows developers to change content, styles, and attributes dynamically.
          Events: JavaScript can handle events such as clicks, form submissions, and mouse movements, allowing for interactive functionality.
          APIs: JavaScript can interact with various web APIs to fetch data, handle user inputs, and integrate with other web services.
          How They Work Together in Projects
          1:HTML provides the structure of the webpage:
          <html>
            <head>
              <link rel="stylesheet" type="text/css" href="styles.css">
            </head>
            <body>
              <div class="container">
                <h1 id="title">Hello, World!</h1>
                <button id="changeText">Change Text</button>
              </div>
              <script src="script.js"></script>
            </body>
          </html>
          2:CSS styles the webpage:
          .container {
            text-align: center;
            margin-top: 50px;
          }
          #title {
            color: blue;
            font-size: 2em;
          }
          button {
            padding: 10px 20px;
            background-color: green;
            color: white;
            border: none;
            cursor: pointer;
          }
          3:JavaScript adds interactivity:
          document.getElementById('changeText').addEventListener('click', function() {  
            document.getElementById('title').textContent = 'Text Changed!';
          });
          Integration in Projects:
          Static Content: HTML provides the static content and structure of the web page.
          Styling: CSS is used to apply consistent styling across the web page, ensuring a visually appealing design.
          Interactivity: JavaScript brings the web page to life by handling user interactions, updating content dynamically, and communicating with web servers.
          In a typical web development project, these three technologies are used together to build comprehensive, interactive, and visually appealing web applications.
