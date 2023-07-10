**Lab Exercise: Your First JavaScript Function**

**Objective:** In this lab, you will write your first JavaScript function. The objective is to create a JavaScript function that returns "Hello, World!" and then print this result to the console using `console.log()`.

**Challenge Goal:** Modify your function to accept your name as a parameter and return "Hello, Your Name!" where "Your Name" is your actual name.

**Estimated Time to Complete:** 45 minutes

**Instructions:**

1. **Create a JavaScript file:**
    - Open the file `src/greeting.js`.

2. **Write your first JavaScript function:**
    - In the newly created file, type the following code to create your function:
        ```javascript
        function greeting() {
          return "Hello, World!";
        }
        ```
    - Now let's call our function and log its result to the console:
        ```javascript
        console.log(greeting());
        ```
    - Your complete code should look like this:
        ```javascript
        function greeting() {
          return "Hello, World!";
        }
        
        console.log(greeting());
        ```
    - Save the file again using `Ctrl + S` or "File" > "Save".

3. **Run your JavaScript function:**
    - Open the terminal in Visual Studio Code by clicking on "Terminal" > "New Terminal" or using the shortcut `Ctrl + ` (backtick, usually below the Esc key).
    - In the terminal, navigate to the directory where you saved your JavaScript file. You can change the directory using the `cd` command followed by the directory path. For example, if you saved your file in a directory named "JS_Labs" on the desktop, you would type `cd Desktop/JS_Labs` (assuming you are in the home directory).
    - Once you're in the correct directory, type `node greeting.js` in the terminal and press Enter. This command tells Node.js to run your file.
    - You should see "Hello, World!" printed in the terminal. Congrats on running your first JavaScript function!

4. **Challenge Goal:**
    - Now modify your function to accept a parameter and use this in the return value. Your function should now look like this:
        ```javascript
        function greeting(name) {
          return "Hello, " + name + "!";
        }
        ```
    - Replace the function call in the `console.log()` with your name as an argument. For example, if your name is John, your `console.log()` would look like this:
        ```javascript
        console.log(greeting("John"));
        ```
    - Your complete code should look like this:
        ```javascript
        function greeting(name) {
          return "Hello, " + name + "!";
        }
        
        console.log(greeting("John"));
        ```
    - Save and run your code again using the steps described above. Your personalized greeting should be printed in the console.

Congratulations, you've written your first JavaScript function and completed this lab!

**Note:** Coding is about learning through trial and error. Mistakes are part of the process. Don't be discouraged if you make some, they're an essential part of the learning process.