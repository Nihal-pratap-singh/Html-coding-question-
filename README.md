# Html-coding-question-

Sure! Here are the answers to all 50 HTML coding questions:

1. **Basic structure of an HTML5 document:**
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Document</title>
   </head>
   <body>
       
   </body>
   </html>
   ```

2. **HTML page with a title "My First Page" and a heading "Hello, World!":**
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>My First Page</title>
   </head>
   <body>
       <h1>Hello, World!</h1>
   </body>
   </html>
   ```

3. **Create a hyperlink that opens in a new tab:**
   ```html
   <a href="https://www.example.com" target="_blank">Visit Example</a>
   ```

4. **Embed an image with alternate text:**
   ```html
   <img src="images/photo.jpg" alt="My Photo">
   ```

5. **Create an unordered list with three items:**
   ```html
   <ul>
       <li>Apple</li>
       <li>Banana</li>
       <li>Cherry</li>
   </ul>
   ```

6. **Create an ordered list with three items:**
   ```html
   <ol>
       <li>First</li>
       <li>Second</li>
       <li>Third</li>
   </ol>
   ```

7. **Create a table with 2 rows and 3 columns:**
   ```html
   <table>
       <tr>
           <td>Row 1, Cell 1</td>
           <td>Row 1, Cell 2</td>
           <td>Row 1, Cell 3</td>
       </tr>
       <tr>
           <td>Row 2, Cell 1</td>
           <td>Row 2, Cell 2</td>
           <td>Row 2, Cell 3</td>
       </tr>
   </table>
   ```

8. **Create a form with inputs for "Username", "Password", and a "Submit" button:**
   ```html
   <form>
       <label for="username">Username:</label>
       <input type="text" id="username" name="username"><br><br>
       <label for="password">Password:</label>
       <input type="password" id="password" name="password"><br><br>
       <input type="submit" value="Submit">
   </form>
   ```

9. **Create a drop-down list with options "Red", "Green", and "Blue":**
   ```html
   <select>
       <option value="red">Red</option>
       <option value="green">Green</option>
       <option value="blue">Blue</option>
   </select>
   ```

10. **Create a multi-line text input area in a form:**
    ```html
    <textarea rows="4" cols="50" name="comment" form="usrform">Enter text here...</textarea>
    ```

11. **Create a hyperlink that links to `https://www.example.com` with the text "Visit Example":**
    ```html
    <a href="https://www.example.com">Visit Example</a>
    ```

12. **Embed a YouTube video in an HTML document:**
    ```html
    <iframe width="560" height="315" src="https://www.youtube.com/embed/your-video-id" frameborder="0" allowfullscreen></iframe>
    ```

13. **Create a checkbox group with three options: "HTML", "CSS", "JavaScript":**
    ```html
    <form>
        <input type="checkbox" id="html" name="skills" value="HTML">
        <label for="html"> HTML</label><br>
        <input type="checkbox" id="css" name="skills" value="CSS">
        <label for="css"> CSS</label><br>
        <input type="checkbox" id="javascript" name="skills" value="JavaScript">
        <label for="javascript"> JavaScript</label><br>
    </form>
    ```

14. **Create a radio button group for selecting gender with options "Male", "Female":**
    ```html
    <form>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br>
    </form>
    ```

15. **Create a table with a header row containing "Name", "Age", and "Email":**
    ```html
    <table>
        <tr>
            <th>Name</th>
            <th>Age</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>30</td>
            <td>john@example.com</td>
        </tr>
    </table>
    ```

16. **Add a comment in an HTML document:**
    ```html
    <!-- This is a comment -->
    ```

17. **Include an external CSS file in an HTML document:**
    ```html
    <link rel="stylesheet" href="styles.css">
    ```

18. **Create a link that jumps to a specific section of the same page with an ID of "section1":**
    ```html
    <a href="#section1">Go to Section 1</a>

    <div id="section1">
        <h2>Section 1</h2>
        <p>This is section 1.</p>
    </div>
    ```

19. **Create an image map with clickable areas:**
    ```html
    <img src="image.jpg" usemap="#image-map">

    <map name="image-map">
        <area shape="rect" coords="34,44,270,350" href="https://www.example.com" alt="Example">
    </map>
    ```

20. **Create a button that submits a form:**
    ```html
    <form>
        <input type="submit" value="Submit">
    </form>
    ```

21. **Create an HTML document with a meta description:**
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description" content="This is a sample page">
        <title>Document</title>
    </head>
    <body>
        
    </body>
    </html>
    ```

22. **Create a form that uses the POST method to submit data to `submit.php`:**
    ```html
    <form action="submit.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <input type="submit" value="Submit">
    </form>
    ```

23. **Make an image a hyperlink:**
    ```html
    <a href="https://www.example.com">
        <img src="image.jpg" alt="Example">
    </a>
    ```

24. **Create a simple HTML5 audio player:**
    ```html
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    ```

25. **Create a simple HTML5 video player:**
    ```html
    <video width="320" height="240" controls>
        <source src="movie.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    ```

26. **Create a definition list with two items:**
    ```html
    <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets</dd>
    </dl>
    ```

27. **Create a responsive image that adjusts to the width of its container:**
    ```html
    <img src="image.jpg" style="width: 100%; height: auto;" alt="Responsive Image">
    ```

28. **Use the `<figure>` and `<figcaption>` tags to add a caption to an image:**
    ```html
    <figure>
        <img src="image.jpg" alt="Sample Image">
        <figcaption>Caption for the image.</figcaption>
    </figure>
    ```

29. **Create an input field that only accepts numbers:**
    ```html
    <input type="number" id="quantity" name="quantity" min="1" max="5">
    ```

30. **Create an email input field in a form:**
    ```html
    <form>
        <label for="email">Email:</label>
        <input type="email"

 id="email" name="email">
    </form>
    ```

31. **Create a form input field with a placeholder text "Enter your name":**
    ```html
    <input type="text" placeholder="Enter your name">
    ```

32. **Create a hidden input field in a form:**
    ```html
    <form>
        <input type="hidden" name="userId" value="12345">
    </form>
    ```

33. **Create an input field with a default value of "John Doe":**
    ```html
    <input type="text" value="John Doe">
    ```

34. **Create a button that resets all form fields:**
    ```html
    <form>
        <input type="reset" value="Reset">
    </form>
    ```

35. **Create a progress bar in HTML5:**
    ```html
    <progress value="70" max="100"></progress>
    ```

36. **Create a navigation bar with links to "Home", "About", and "Contact":**
    ```html
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    ```

37. **Create a footer section in an HTML document:**
    ```html
    <footer>
        <p>&copy; 2023 My Website</p>
    </footer>
    ```

38. **Create a contact form with fields for "Name", "Email", "Message", and a "Submit" button:**
    ```html
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
        <input type="submit" value="Submit">
    </form>
    ```

39. **Include a JavaScript file in an HTML document:**
    ```html
    <script src="script.js"></script>
    ```

40. **Create a clickable button that runs a JavaScript function when clicked:**
    ```html
    <button onclick="myFunction()">Click me</button>

    <script>
    function myFunction() {
        alert("Button clicked!");
    }
    </script>
    ```

41. **Add a favicon to an HTML document:**
    ```html
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    ```

42. **Create a table with a caption "Student Grades" and two columns "Name" and "Grade":**
    ```html
    <table>
        <caption>Student Grades</caption>
        <tr>
            <th>Name</th>
            <th>Grade</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>A</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>B</td>
        </tr>
    </table>
    ```

43. **Create a horizontal rule in HTML:**
    ```html
    <hr
