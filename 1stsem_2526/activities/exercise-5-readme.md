## Exercise 5 CSS formatting text
1. 1. Copy [exercise5-css-formatting.html](https://github.com/milkylee/webdesign2526/blob/master/1stsem_2526/activities/exercise5-css-formatting.html) and paste in notepad save as exercise4-form-and-css-(your-name).html
2. We’re going to use an embedded style sheet for this exercise. Start by adding a style element with its required type attribute to the head of the document (remember, the only place a style element can go is in the head)
    body {
            font-family: verdana, sans-serif;
            font-size: 12px;
        }

        #header {
            background: #ccc;
            padding: 20px;
        }

        #sidebar {
            margin: 0;
            padding: 0;
            width: 200px;
            background-color: #f1f1f1;
            position: absolute;
            height: 100%;
        }

        /* Sidebar links */
        #sidebar a {
            display: block;
            color: black;
            padding: 16px;
            text-decoration: none;
        }

        /* Active/current link */
        #sidebar a.active {
            background-color: #04AA6D;
            color: white;
        }

        /* Links on mouse-over */
        #sidebar a:hover:not(.active) {
            background-color: #555;
            color: white;
        }

        #content {
            margin-left: 12%;
        }

        #footer {
            position: absolute;
            bottom: 10;
            width: 100%;
            height: 60px;
            background-color: #f5f5f5;
        }
3. First, I have a few global changes to the body element in mind. I’ve had a change of heart about the font-family . I think that a monospace font such as Courier New would be more sophisticated and appropriate for the academic page. Let’s also use the line-height property to open up the text lines and make them easier to read and set it to 105%. Make these updates to the body style rule.
4. I’m going to center a few key elements on the page using the text-align property. Write a rule with a grouped selector to center the whole header div, the strong elements. Instead of large, bold type, I’m actually going to use all uppercase letters, extra letter spacing to 8px, and color to call attention to the headings.
5. Add a rule using contextual selectors that makes the paragraphs in the intro class italic.
6. Finally, we’ll add a softer color to the menu item names (in ul elements). Use any RGB colors.

Output:
![Figure 5](/1stsem_2526/activities/exercise-5.png)

